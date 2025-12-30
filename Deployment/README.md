# 🚀 Deployment Strategy & Orchestration

มาตรฐานการติดตั้งระบบ (Deployment) การจัดการ Container และการทำ Automation Workflow



## 📦 Containerization Technology
การทำ Application Virtualization ในระดับ OS Level

* **Docker Engine:** Runtime Environment สำหรับรัน Container
* **OCI Standard:** มาตรฐาน Image Format ที่ใช้งานได้กับทุก Runtime
* **Dockerfile Best Practices:**
    * *Multi-stage Build:* เพื่อลดขนาด Image Size
    * *Layer Caching:* การเรียงคำสั่งเพื่อ Optimize การ Build
    * *Non-root User:* การรัน Container ด้วย User สิทธิ์ต่ำเพื่อความปลอดภัย

---

## 🎼 Container Orchestration (Kubernetes)
ระบบจัดการ Cluster เพื่อรองรับ High Availability (HA) และ Scalability

* **Pod:** หน่วยเล็กที่สุดใน K8s (1 Pod อาจมีหลาย Container)
* **Service:** การจัดการ Networking และ Load Balancing ภายใน Cluster
* **Ingress:** Gateway สำหรับ Routing Traffic จากภายนอกเข้าสู่ Service
* **ConfigMap / Secret:** การแยก Configuration ออกจาก Application Logic

---

## 🤖 Automation Workflow (GitOps)
แนวคิดการใช้ Git Repository เป็น Single Source of Truth สำหรับ Infrastructure

* **Workflow Engine:** GitHub Actions / GitLab CI
* **Triggers:**
    * *Push Event:* รัน Pipeline เมื่อมีการแก้ไข Code
    * *Pull Request:* รัน Test ก่อนการ Merge
* **Self-hosted Runners:** การใช้ Server ส่วนตัวในการรัน Pipeline เพื่อความปลอดภัยและ Performance
