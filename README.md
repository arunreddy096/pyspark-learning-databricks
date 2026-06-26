# PySpark for Data Engineers on Databricks — Complete Learning Plan

A hands-on PySpark learning series covering everything a data engineer needs to build production pipelines on Databricks.

## 📚 Curriculum

| Phase | Topic | Key Skills |
| --- | --- | --- |
| **0 & 1** | Spark Foundations | Architecture, lazy evaluation, partitions, DAGs, wide vs narrow transforms |
| **2** | DataFrame API | Select, filter, groupBy, joins, window functions, UDFs |
| **3** | Reading & Writing Data | CSV/JSON/Parquet/Delta, save modes, schema, Auto Loader |
| **4** | Delta Lake Deep Dive | MERGE, OPTIMIZE, Z-ORDER, Liquid Clustering, VACUUM, CDF |
| **5** | Performance Tuning | Shuffle tuning, caching, broadcast joins, data skew, predicate pushdown |
| **6** | Structured Streaming | Triggers, output modes, watermarks, windowed aggregations, stream-stream joins |
| **7** | Advanced Transformations | Complex types, explode, higher-order functions, pivot, JSON, regex, dates |
| **8** | Best Practices | Code organization, error handling, logging, idempotency, testing, anti-patterns |

## 🛠️ Environment

- **Databricks Runtime:** 17.3 (Spark Connect)
- **Cluster:** Standard_D8pds_v6, 1-2 workers
- **Catalog:** `arnalladatabricks`
- **Schema:** `arnalladatabricks.pyspark_learning`
- **Volume:** `/Volumes/arnalladatabricks/pyspark_learning/raw_data`

## 🚀 How to Use

1. Open each notebook in order (Phase 0 → Phase 8)
2. Run all cells top to bottom
3. Read the Deep Dive markdown sections for conceptual understanding
4. Complete the checkpoint at the end of each phase

## 📋 Prerequisites

- Databricks workspace with Unity Catalog enabled
- Basic Python knowledge
- Access to `samples.tpch` dataset (pre-loaded in all Databricks workspaces)

## 🎯 What's Next?

After completing this series, you're ready for the **hands-on project course**:
- Medallion Architecture (Bronze / Silver / Gold)
- Lakeflow Declarative Pipelines
- Lakeflow Jobs & Orchestration
- CI/CD with Declarative Automation Bundles
- Unity Catalog Governance & Security



---

**Author:** Arun Reddy  
**Platform:** Databricks on Azure
