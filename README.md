<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3200&pause=900&color=1D6A86&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Abhishek+%F0%9F%91%8B;Azure+%26+Databricks+Data+Engineer;Bronze+%E2%86%92+Silver+%E2%86%92+Gold;Messy+sources+in.+Trusted+tables+out." alt="Azure and Databricks Data Engineer" />

<a href="https://www.linkedin.com/in/abhishek-reddy-manam"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<img src="https://img.shields.io/badge/Open%20to-Data%20Engineer%20roles-1F7A4D?style=flat-square" alt="Open to Data Engineer roles" />
<img src="https://img.shields.io/badge/Databricks-Certified%20DE%20Associate-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks Certified Data Engineer Associate" />

</div>

---

### `> query profile`

```sql
SELECT name, role, years_experience, home_stack, currently
FROM   engineers
WHERE  github_handle = 'Abhi-shek-reddy';
```

| name | role | years_experience | home_stack | currently |
|---|---|---|---|---|
| Abhishek Reddy Manam | Data Engineer @ Tech Impact (DataLab) | 3+ | Azure · Databricks · PySpark · Delta Lake | Shipping Azure pipelines & AI data backends · studying for DP-700 |

<sub>1 row returned · 0 nulls · schema validated ✓</sub>

---

### 🥉 → 🥈 → 🥇 &nbsp;My career, as a medallion pipeline

```mermaid
flowchart LR
    subgraph B["🥉 Bronze · raw ingest"]
        B1["Blockysite<br/>Intern → Associate DE<br/>2021–2023<br/><i>PySpark, ADF, Synapse, dbt</i>"]
    end
    subgraph S["🥈 Silver · cleaned & scaled"]
        S1["Digiuniv Technologies<br/>Data Engineer<br/>2023–2024<br/><i>lakehouse, tuning, data quality</i>"]
    end
    subgraph E["📚 Enrichment"]
        E1["M.S. Information Systems<br/>Wilmington University<br/>2026"]
    end
    subgraph G["🥇 Gold · production-ready"]
        G1["Tech Impact DataLab<br/>Data Engineer<br/>2026 → now<br/><i>Azure Functions, SQL Server ETL,<br/>pgvector search, AI workflows</i>"]
    end
    B1 --> S1 --> E1 --> G1
```

---

### 📊 Pipeline run metrics

| job | before | after |
|---|---|---|
| New-source onboarding (metadata-driven ADF, 40+ linked services) | 3 days | **< 2 hours** |
| Spark job latency (skew fixes, broadcast joins, partition sizing) | baseline | **~50% faster** |
| Data-quality incidents (Great Expectations + dbt tests as CI gates) | baseline | **~40% fewer** |
| Mean time to resolve incidents (runbooks for 15+ failure patterns) | 2 hours | **30 minutes** |
| CI build time (dbt Slim CI) | baseline | **70% shorter** |

---

### 🧰 Stack

**Azure** &nbsp;
![ADF](https://img.shields.io/badge/Data%20Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![ADLS](https://img.shields.io/badge/ADLS%20Gen2-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Synapse](https://img.shields.io/badge/Synapse-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Functions](https://img.shields.io/badge/Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white)
![Fabric](https://img.shields.io/badge/Fabric-117865?style=flat-square&logo=microsoft&logoColor=white)
![DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)

**Lakehouse & processing** &nbsp;
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)
![Unity Catalog](https://img.shields.io/badge/Unity%20Catalog-1B3139?style=flat-square&logo=databricks&logoColor=white)

**Warehouse & modeling** &nbsp;
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Orchestration, quality & code** &nbsp;
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great%20Expectations-FF6310?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### ⏱️ Currently running jobs

```text
JOB                         STATUS     NOTE
dp700_fabric_certification  RUNNING    Microsoft Fabric Data Engineer, in progress
job_scout_pipeline          BUILDING   my own ETL that scrapes, scores and ranks job postings
open_to_work                ACTIVE     Data Engineer roles · US · remote / hybrid / onsite, happy to relocate
```

### ✅ Data quality checks on me

```yaml
expect_column_values_to_not_be_null:  [curiosity, ownership, documentation]
expect_column_values_to_be_unique:    "explains pipelines to non-engineers"
expect_table_row_count_to_increase:   skills   # every quarter
```

---

<div align="center">
<sub>Pipelines should be boring in production. Everything else can be interesting. · <a href="https://www.linkedin.com/in/abhishek-reddy-manam">Let's talk data</a></sub>
</div>
