# nd2-learning-journey-2025

> **Description:** พื้นที่รวบรวมองค์ความรู้เกี่ยวกับการพัฒนาระบบอัตโนมัติ (Automation), DevOps Pipeline, การจัดการข้อมูล (Data & AI) และการวางระบบ Deployment

![Status](https://img.shields.io/badge/Status-Active-success)
![Platform](https://img.shields.io/badge/Platform-Docker%20%7C%20K8s%20%7C%20Cloud-blue)
![Language](https://img.shields.io/badge/Language-Python%20%7C%20Go%20%7C%20JS-yellow)

---

## 📑 สารบัญ (Table of Contents)

1. [DevOps Concepts for Automation Systems](#-devops-concepts-for-automation-systems)
2. [Front-End & Back-End](#-front-end--back-end)
3. [Data Processing and AI](#-data-processing-and-ai)
4. [Deployment & Automation Workflow](#-deployment--automation-workflow)
5. [Future Works/Projects](#-future-worksprojects)

---

## ♾️ DevOps Concepts for Automation Systems

หลักการและทฤษฎีพื้นฐานของ DevOps เพื่อเพิ่มประสิทธิภาพระบบอัตโนมัติ

> 📂 **Documentation:** [ดูข้อมูลโดยละเอียดได้ในโฟลเดอร์ DevOps-Concepts](./DevOps-Concepts/README.md)

* **Culture & Philosophy:** การทำงานร่วมกันระหว่าง Development และ Operations (CAMS Model)
* **CI/CD Pipelines:**
    * *Continuous Integration (CI):* การรวมโค้ดและทดสอบอัตโนมัติ
    * *Continuous Delivery/Deployment (CD):* การส่งมอบซอฟต์แวร์สู่ Production
* **Infrastructure as Code (IaC):** การจัดการโครงสร้างพื้นฐานผ่านโค้ด (Terraform, Ansible)
* **Monitoring & Logging:** การเฝ้าระวังระบบแบบ Real-time (Prometheus, Grafana, ELK Stack)

---

## 💻 Front-End & Back-End

การพัฒนาส่วนติดต่อผู้ใช้และระบบเบื้องหลัง

> 📂 **Documentation:** [ดูข้อมูลโดยละเอียดได้ในโฟลเดอร์ Frontend-Backend](./Frontend-Backend/README.md)

* **Front-End Development:**
    * *Frameworks:* React, Vue.js, หรือ Next.js สำหรับ Web Interface
    * *UI/UX:* การออกแบบ Dashboard สำหรับควบคุมระบบ Automation
* **Back-End Development:**
    * *API Design:* RESTful API และ GraphQL
    * *Microservices:* การออกแบบระบบเป็นบริการย่อยเพื่อความยืดหยุ่น
    * *Languages:* Node.js, Python (FastAPI/Django), Go

---

## 🧠 Data Processing and AI

กระบวนการจัดการข้อมูลและการนำปัญญาประดิษฐ์มาประยุกต์ใช้

> 📂 **Documentation:** [ดูข้อมูลโดยละเอียดได้ในโฟลเดอร์ Data-AI](./Data-AI/README.md)

* **Data Engineering:**
    * *ETL Pipelines:* การดึง (Extract), แปลง (Transform), และโหลด (Load) ข้อมูล (Airflow)
    * *Database:* SQL (PostgreSQL) และ NoSQL (MongoDB, InfluxDB)
* **Artificial Intelligence (AI):**
    * *Machine Learning:* Model Training สำหรับทำ Predictive Maintenance
    * *Computer Vision:* การประมวลผลภาพสำหรับตรวจสอบคุณภาพ (QC Automation)
    * *Model Serving:* การนำโมเดลไปใช้งานจริงผ่าน API

---

## 🚀 Deployment & Automation Workflow

ขั้นตอนการติดตั้งระบบและการจัดการ Workflow อัตโนมัติ

> 📂 **Documentation:** [ดูข้อมูลโดยละเอียดได้ในโฟลเดอร์ Deployment](./Deployment/README.md)

* **Containerization:**
    * *Docker:* การสร้าง Image และ Container สำหรับ Application
    * *Docker Compose:* การจัดการ Multi-container applications
* **Orchestration:**
    * *Kubernetes (K8s):* การจัดการ Scaling และ Deployment ระดับ Cluster
* **Automation Tools:**
    * *GitHub Actions / GitLab CI:* Workflow สำหรับ Automated Testing และ Deploy
    * *Scripts:* Shell Scripting/Python สำหรับงาน Routine Tasks

---

## 🔮 Future Works/Projects

แผนงานในอนาคตและโปรเจกต์ที่กำลังพัฒนา

> 📂 **Documentation:** [ดูข้อมูลโดยละเอียดได้ในโฟลเดอร์ Future-Works](./Future-Works/README.md)

- [ ] **Auto-Scaling System:** พัฒนาระบบขยาย Server อัตโนมัติตามปริมาณ Load
- [ ] **AI-Powered Anomaly Detection:** ตรวจจับความผิดปกติของระบบ Server ด้วย AI
- [ ] **Serverless Architecture:** ย้ายฟังก์ชันบางส่วนไปใช้ AWS Lambda/Google Cloud Functions
- [ ] **Centralized Log Management:** รวม Log จากทุก Service มาไว้ที่เดียวแบบครบวงจร
