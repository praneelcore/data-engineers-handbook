# Data Engineering Bootcamp

A free, comprehensive, hands-on learning path for data engineering — from SQL basics to production-grade Lakehouse pipelines, plus Python DSA for interview prep.

**66 Databricks notebooks + 9 DSA notebooks = 75 total resources, 2,600+ cells of content.**

---

## Who Is This For?

- Career changers breaking into data engineering
- Junior DEs leveling up to senior
- Software engineers transitioning to DE
- Anyone preparing for DE interviews at top companies

## What You'll Learn

By the end of this series, you'll be able to:
- Write production SQL and PySpark at scale
- Design and build Medallion architecture pipelines
- Implement streaming, CDC, and real-time processing
- Use Delta Lake, Unity Catalog, and Databricks platform
- Pass Databricks certification exams
- Ace DE interviews (coding, system design, behavioral)

---

## Learning Path

### Phase 0: Getting Started
| # | Notebook | Description |
|---|----------|-------------|
| 00 | `databricks_environment_setup` | Databricks compatibility rules and environment reference |
| 01 | `what_is_data_engineering` | Complete DE overview, lifecycle, career paths |
| 02 | `linux_essentials` | Essential commands, shell scripting, Docker basics |
| 03 | `git_and_github` | Version control, branching, CI/CD foundations |

### Phase 1: Core Language Foundations
| # | Notebook | Description |
|---|----------|-------------|
| 04 | `cs_fundamentals` | Networking, OS, database internals, distributed systems |
| 05 | `sql_foundations` | SQL mastery + creates all datasets used throughout the series |
| 06 | `sql_advanced_patterns` | Window functions, cohort analysis, CTEs, optimization |
| 07 | `hadoop_ecosystem` | HDFS, MapReduce, YARN, Kafka, Hive — history and concepts |
| 08 | `python_foundations` | Python for DE: types, OOP, error handling, pipeline patterns |
| 09 | `python_advanced_patterns` | Generators, decorators, concurrency, production frameworks |
| 10 | `pyspark_deep_dive` | Spark architecture, DataFrame API, transformations, joins |
| 11 | `pyspark_advanced_patterns` | Complex types, UDFs, broadcast joins, Delta operations |

### Phase 2: Data Theory & Architecture
| # | Notebook | Description |
|---|----------|-------------|
| 12 | `data_modeling` | Kimball, Data Vault, OBT, Activity Schema, SCD types |
| 13 | `lakehouse_architecture` | Lambda, Kappa, Medallion, Data Mesh patterns |

### Phase 3: Core Data Engineering
| # | Notebook | Description |
|---|----------|-------------|
| 14 | `medallion_architecture` | Bronze/Silver/Gold, Delta Lake, incremental processing |
| 15 | `delta_lake_internals` | Transaction log, OPTIMIZE, VACUUM, time travel |
| 16 | `slowly_changing_dimensions` | SCD Types 0-6, MERGE patterns |
| 17 | `change_data_capture` | CDC concepts, Change Data Feed |
| 18 | `lakeflow_declarative_pipelines` | Formerly DLT, expectations, pipeline design |
| 19 | `auto_loader_ingestion` | Schema inference, file detection modes |
| 20 | `structured_streaming` | Watermarks, Kafka, foreachBatch |
| 21 | `apache_kafka` | Architecture, producers, consumers, exactly-once |
| 22 | `apache_flink` | True streaming, windowing, state, checkpointing |
| 23 | `star_schema_modeling` | Dimensional modeling, facts, dimensions |

### Phase 4: Platform & Governance
| # | Notebook | Description |
|---|----------|-------------|
| 24 | `unity_catalog` | Permissions, row/column security, lineage |
| 25 | `data_governance` | Data contracts, classification, policies |
| 26 | `compliance_and_regulations` | GDPR, HIPAA, PCI-DSS, SOX, right to deletion |
| 27 | `performance_optimization` | AQE, Liquid Clustering, Photon, shuffle tuning |
| 28 | `apache_airflow` | DAGs, operators, TaskFlow, production patterns |
| 29 | `orchestration_workflows` | Lakeflow Jobs, DAG design, retry patterns |
| 30 | `data_quality_framework` | Quality dimensions, monitoring, alerting |
| 31 | `cicd_pipelines` | GitHub Actions, testing, deployment strategies |
| 32 | `declarative_automation_bundles` | DABs, multi-environment deployment |

### Phase 5: Ecosystem Tools
| # | Notebook | Description |
|---|----------|-------------|
| 33 | `dbt_for_data_engineering` | Models, tests, macros, incremental processing |
| 34 | `databricks_sql_and_dashboards` | SQL Warehouses, Lakeview, BI queries |
| 35 | `databricks_platform_essentials` | Serverless, Photon, cost optimization |

### Phase 6: Python Libraries for DE
| # | Notebook | Description |
|---|----------|-------------|
| 36-47 | `pandas` → `file_system_operations` | 12 essential Python libraries for production DE |

### Phase 7: Cloud & DevOps
| # | Notebook | Description |
|---|----------|-------------|
| 48 | `cloud_and_devops` | Terraform, Docker, K8s, CI/CD, monitoring |
| 49 | `aws_for_data_engineers` | S3, Glue, EMR, Redshift, Kinesis, Lambda |
| 50 | `multi_cloud_integration` | AWS/Azure/GCP patterns and differences |
| 51 | `apis_and_networking` | REST, OAuth, pagination, webhooks, reverse ETL |

### Phase 8: Advanced Topics
| # | Notebook | Description |
|---|----------|-------------|
| 52 | `ai_and_ml_engineering` | Feature stores, RAG, LLMs, MLOps for DE |
| 53 | `ai_ml_on_databricks` | MLflow, Feature Store, Model Serving |
| 54 | `databricks_ai_dev_kit` | AI-assisted development tools |
| 55 | `system_design` | End-to-end pipeline design, 6 case studies |
| 56 | `business_acumen_and_metrics` | KPIs, revenue metrics, stakeholder communication |

### Phase 9: Capstone Projects
| # | Notebook | Description |
|---|----------|-------------|
| 57 | `capstone_ecommerce` | Full e-commerce data platform |
| 58 | `capstone_fintech` | FinTech pipeline |
| 59 | `capstone_iot` | IoT sensor data pipeline |
| 60 | `capstone_streaming` | Real-time streaming analytics |
| 61 | `capstone_governance` | Governance and quality platform |
| 62 | `capstone_orchestrated` | Multi-domain orchestrated platform |
| 63 | `capstone_modern_platform` | Ultimate AI-powered lakehouse |

### Phase 10: Career
| # | Notebook | Description |
|---|----------|-------------|
| 64 | `career_and_interview_prep` | Resume, behavioral, salary negotiation |
| 65 | `certification_guide` | Databricks certification mapping and prep |

---

## Python DSA Series (Interview Prep)

Pure Python — runs anywhere (no Spark needed). Located in `dsa/notebooks/`.

| # | Notebook | Topics |
|---|----------|--------|
| 00 | Introduction | What is DSA, Python refresher, first problems |
| 01 | Complexity Analysis | Big-O, space complexity, timing demos |
| 02 | Arrays, Strings & Hash Maps | Two pointers, sliding window, frequency counting |
| 03 | Linked Lists, Stacks & Queues | Fast/slow pointers, monotonic stack |
| 04 | Trees & Heaps | Traversals, BST, priority queues, top-K |
| 05 | Graphs | BFS, DFS, topological sort, Dijkstra, Union-Find |
| 06 | Recursion, Backtracking & DP | Memoization, knapsack, LCS |
| 07 | Sorting, Searching & Greedy | Binary search, merge sort, intervals |
| 08 | Interview Patterns & Mock | 15 patterns, 10 mock problems |

---

## Getting Started

### For Databricks Notebooks (04-65)

1. Create a free [Databricks Community Edition](https://community.cloud.databricks.com) account
2. Import `.ipynb` files from the `notebooks/` folder
3. **Start with notebook 04** — it creates the `techmart_dw` database that all subsequent notebooks use
4. Run notebooks in order

### For DSA Notebooks (00-08)

```bash
pip install jupyter
jupyter notebook dsa/notebooks/
# Or upload to Google Colab / Databricks
```

---

## Technologies Covered

| Category | Technologies |
|----------|-------------|
| **Languages** | SQL, Python, PySpark |
| **Processing** | Apache Spark, Flink, dbt |
| **Storage** | Delta Lake, Parquet, S3, Redshift |
| **Streaming** | Apache Kafka, Structured Streaming, Kinesis |
| **Orchestration** | Apache Airflow, Databricks Workflows |
| **Cloud** | AWS (S3, Glue, EMR, Redshift, Lambda), Azure, GCP |
| **Platform** | Databricks, Unity Catalog, MLflow |
| **DevOps** | Docker, Kubernetes, Terraform, GitHub Actions |
| **Governance** | GDPR, HIPAA, PCI-DSS, data classification |

---

## Repository Structure

```
├── README.md
├── notebooks/              ← 66 Databricks DE notebooks (00-65)
├── dsa/
│   └── notebooks/          ← 9 Python DSA notebooks
├── resources/
│   └── LEARNING_PLAN.md
└── HOW_NOTEBOOKS_WERE_CREATED.txt
```

---

## Contributing

Found an error or want to improve content? PRs are welcome.

---

## License

This project is for educational purposes. Free to use for personal learning.
Databricks, Delta Lake, and related trademarks belong to their respective owners.
