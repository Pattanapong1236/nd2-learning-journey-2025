# 🔭 Engineering Roadmap & Project Tracker

เอกสารติดตามสถานะการพัฒนา (Development Status), การจัดการหนี้ทางเทคนิค (Technical Debt), และแผนงานในอนาคต

## 📊 Project Portfolio Matrix

| Project Code | Module Name | Engineering Goal | Priority | Tech Stack | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **SYS-01** | **Auto-Scaling Infrastructure** | Implement HPA (Horizontal Pod Autoscaler) on K8s | High | Terraform, AWS EKS | 🟢 Stable |
| **AI-02** | **Anomaly Detection Model** | Reduce Inference Latency < 100ms | Medium | Python, ONNX Runtime | 🟡 Development |
| **MON-03** | **Centralized Logging** | Unified Log Aggregation with retention policy | High | ELK Stack, Filebeat | 🔴 Planning |

---

## 🛠️ Technical Debt & Refactoring Plan
รายการสิ่งที่ต้องปรับปรุงโครงสร้างเพื่อความยั่งยืนของระบบ (Maintainability)

* [ ] **Refactor API Authentication:** เปลี่ยนจาก Basic Auth เป็น OAuth2/JWT เพื่อความปลอดภัย
* [ ] **Database Indexing Optimization:** วิเคราะห์ Query Plan และสร้าง Index เพื่อลด Query Time
* [ ] **Migrate to Microservices:** แยก Module การแจ้งเตือน (Notification Service) ออกจาก Monolith

---

## 🔮 Future Architecture Roadmap
* **Serverless Adoption:** การย้าย Event-driven functions ไปใช้ Serverless (AWS Lambda) เพื่อลด Cost
* **Edge AI Deployment:** การทำ Model Quantization เพื่อรันบน Microcontroller
* **Chaos Engineering:** การทดสอบความทนทานของระบบโดยการจำลองการล่ม (Fault Injection)
