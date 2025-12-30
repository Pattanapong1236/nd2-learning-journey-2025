# 💻 Full-Stack Architecture (Client-Server Model)

เอกสารระบุรายละเอียดทางเทคนิคของสถาปัตยกรรมส่วนติดต่อผู้ใช้ (Frontend) และระบบประมวลผล (Backend)

## 🎨 Client-Side Engineering (Front-End)
สถาปัตยกรรม Single Page Application (SPA) และการจัดการ State

* **Component-Based Architecture:** การออกแบบ UI เป็นโมดูลย่อย (Reusable Components)
* **Virtual DOM:** เทคนิคการอัปเดตหน้าจอโดยคำนวณความเปลี่ยนแปลงใน Memory ก่อน Render จริง (React/Vue)
* **State Management:** การจัดการ Data Flow ภายในแอปพลิเคชัน (Redux, Pinia, Context API)
* **Build Tools:** กระบวนการ Transpile และ Bundle Code (Webpack, Vite)

---

## ⚙️ Server-Side Engineering (Back-End)
การออกแบบ Business Logic และ Data Persistence Layer

### Architectural Styles
1.  **Monolithic:** รวมทุก Service ไว้ใน Process เดียว (ดูแลง่าย แต่ Scale ยาก)
2.  **Microservices:** แยก Service ตาม Domain (Scale แยกได้, Complexity สูง)

### API Specifications
มาตรฐานการแลกเปลี่ยนข้อมูลระหว่าง Client และ Server
* **RESTful API:** สถาปัตยกรรมแบบ Stateless โดยใช้ HTTP Methods (GET, POST, PUT, DELETE)
* **GraphQL:** การ Query ข้อมูลแบบยืดหยุ่น Client เลือก Field ที่ต้องการได้เอง
* **gRPC:** การสื่อสารแบบ High Performance ด้วย Protocol Buffers (เหมาะกับ Inter-service communication)

---

## 🗄️ Database Design
* **Relational Database (RDBMS):** เน้นความถูกต้องของข้อมูล (ACID Properties) และการทำ Normalization (PostgreSQL, MySQL)
* **NoSQL:** เน้นความยืดหยุ่นและการรองรับ Unstructured Data (MongoDB, Redis, InfluxDB for Time-series)
