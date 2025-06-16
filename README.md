# aws-superstore-data-pipeline
End-to-end AWS cloud analytics solution using S3, Glue, Athena, and QuickSight.


# AWS Superstore Data Pipeline (Research-Oriented Project)

This project demonstrates an **end-to-end cloud-based data pipeline** built using Amazon Web Services (AWS) to analyze a retail Superstore dataset. It was developed as a practical demonstration of business intelligence (BI) and cloud-native data engineering.

📁 **Files Included**
- `AWS SuperStore Project Report.docx` — Full write-up with architecture, queries, challenges, and lessons learned.
- `AWS-Based Superstore Data Analysis.pptx` — Visual presentation summarizing goals, architecture, and key results.

---

## ☁️ AWS Architecture

- **Amazon S3** – Storage for raw and partitioned sales data
- **AWS Glue** – Schema crawler + data catalog creation
- **Amazon Athena** – Serverless SQL querying for interactive analysis
- **Amazon QuickSight** – BI dashboards for visualizing sales insights

### 📊 Analytical Focus
- Sales trends by product category
- Customer segmentation
- Revenue analysis over time
- Query optimization via S3 partitioning

---

## 🔧 Implementation Highlights

| Component     | Role                                         |
|---------------|----------------------------------------------|
| **S3**        | Object storage for order snapshots           |
| **Glue**      | Automatic schema detection (crawler)         |
| **Athena**    | SQL-based querying, serverless and scalable  |
| **QuickSight**| Dashboards connected directly to Athena      |

- Folder structure (`snapshot_day=YYYY-MM-DD`) enabled partitioning
- Query output locations configured to reduce errors
- IAM permissions applied for least privilege

---

## 🚀 Key Skills Demonstrated

- ✅ AWS Glue Crawler Setup & Metadata Cataloging
- ✅ S3 Data Management with Partitioning
- ✅ Serverless Querying in Athena
- ✅ BI Visualization via QuickSight
- ✅ IAM Role Configuration & Permission Troubleshooting

---

## 🔄 Challenges Overcome

- Correcting S3 folder structure for Glue partition detection
- Resolving Athena query output errors
- Fixing IAM role trust policies and service permissions

---

## 🧠 Takeaways

- **Partitioning strategy** is critical for optimizing cloud query performance.
- **Serverless architecture** reduces overhead and enables scalable BI.
- **Hands-on AWS experience** with Glue, Athena, and QuickSight is essential for modern data analysts and business intelligence professionals.

---

## 💼 Career Context

This project simulates how companies like **Walmart** and **Expedia** leverage AWS tools for data-driven decisions using scalable, serverless BI infrastructure.

---

**By:** Harry Depina  
**Date:** 2025  
