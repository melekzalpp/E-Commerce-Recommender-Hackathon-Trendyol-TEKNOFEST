# E-Commerce Recommender (Hackathon) — Trendyol × TEKNOFEST

End-to-end two-stage recommender built on a **103M+** row dataset.  
Stage-1: **Candidate generation (recall↑)** → Stage-2: **Re-ranking (LogReg/LightGBM)**.  
**Public Leaderboard:** 0.612 (top 0.712).  
**Period:** Aug 2025 | **Team role:** Data Science.

## 📌 
- Scalable feature engineering with **PySpark**; Spark tuning (shuffle partitions, Kryo, memory).
- Training & inference on **AWS EMR + S3**; IAM role setup and EMR Studio attach fixes.
- Schema-safe Top-K pipeline with **Pandas UDFs** and notebook-first reproducibility.
