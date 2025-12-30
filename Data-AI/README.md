# 🧠 Data Engineering & AI Systems

โครงสร้างระบบการจัดการข้อมูล (Data Pipeline) และกระบวนการพัฒนาโมเดลปัญญาประดิษฐ์ (MLOps)



## 🧱 Data Engineering Pipeline
กระบวนการนำข้อมูลจากแหล่งกำเนิดสู่การใช้งาน (Data Flow Architecture)

### ETL / ELT Process
1.  **Extraction (Ingestion):** การดึงข้อมูลจาก Sources (Sensors, APIs, Logs) รองรับทั้ง Batch และ Streaming (Kafka)
2.  **Transformation (Processing):**
    * *Data Cleaning:* การจัดการ Missing Values และ Outliers
    * *Normalization:* การปรับ Scale ข้อมูล (Min-Max Scaling, Z-Score)
3.  **Loading (Storage):** การจัดเก็บลง Data Warehouse หรือ Data Lake

---

## 🤖 Artificial Intelligence & MLOps
วงจรการพัฒนาระบบ AI ในระดับ Production

### Model Lifecycle
1.  **Feature Engineering:** การคัดเลือกและแปลงข้อมูลดิบให้เป็น Features ที่ Model เข้าใจ
2.  **Training:** การใช้ Algorithm (Neural Networks, Regression) เพื่อหา Weights ที่เหมาะสม
3.  **Validation:** การวัดประสิทธิภาพโมเดล (Confusion Matrix, F1-Score, RMSE)
4.  **Inference:** การนำ Model ไปใช้งานจริง
    * *Edge Inference:* ประมวลผลบนอุปกรณ์ปลายทาง (Latency ต่ำ)
    * *Cloud Inference:* ประมวลผลบน Server (Resource สูง)

### Tech Stack
* **Frameworks:** TensorFlow, PyTorch, Scikit-learn
* **Orchestration:** Apache Airflow (Workflow Management)
