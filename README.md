<div align="center">

# Patrick Okare

**Lead Data Engineer · Databricks · Delta Lake · Snowflake · dbt · Toronto 🇨🇦**

[karetech.ca](https://karetech.ca) · [Medium](https://karetech.medium.com) · [LinkedIn](https://www.linkedin.com/in/patrickokare/)

</div>

---

### Who I am

I design and build enterprise lakehouses on Databricks. Ten-plus years across financial services, healthcare and enterprise SaaS, turning high-volume transactional, ERP and event data into governed, well-modeled data products.

<div align="center">

| **2B–9B records** | **1 hr+ → 7–14 min** | **40–45 hrs / week** |
|:---:|:---:|:---:|
| in the financial data marts I migrated to Databricks | on an 800M+ row workload, using Spark parallelization | of manual reconciliation replaced by automated checks |

</div>

**Selected work:** led Synapse-to-Databricks migrations of financial data marts, consolidating two production Synapse warehouses into a single Unity Catalog medallion architecture.

#### How I work: test-first

Data is proven correct before anyone depends on it.

| Data quality as code | Reconciliation controls | Versioned, tested delivery |
|:---|:---|:---|
| Automated checks for nulls, duplicates, referential integrity and row counts run with every load, so bad data fails the pipeline instead of reaching a dashboard. | Source-to-target checks on row counts and financial totals validate 2B–9B record migrations before cutover. | Schema changes are managed in Liquibase and promoted through GitHub Actions CI/CD, so every change is reviewed, repeatable and reversible. |

#### Right now

- **Currently:** leading enterprise lakehouse delivery on Databricks, building out my portfolio (Formula 1, UK rail, video game sales) and preparing for the Databricks Data Engineer Professional exam
- **Open to:** Senior and Lead Data Engineer or Data Platform roles, and remote data engineering contracts through [KareTech Analytics](https://karetech.ca)
- **Ask me about:** Databricks, Delta Lake, Kimball modeling, Lakeflow pipelines and warehouse migrations

🔗 Consulting: [KareTech Analytics](https://karetech.ca) · Writing: [Medium](https://karetech.medium.com)

---

### Certifications 🏆

![Databricks Certified Data Engineer Associate](https://img.shields.io/badge/Databricks-Certified_Data_Engineer_Associate-FF3621?logo=databricks&logoColor=white) ![Azure Data Engineer Associate DP-203](https://img.shields.io/badge/Microsoft-Azure_Data_Engineer_Associate_DP--203-0078D4?logo=microsoftazure&logoColor=white) ![Fabric Data Warehouse Applied Skills](https://img.shields.io/badge/Microsoft-Applied_Skills_Fabric_Data_Warehouse-117865) ![Azure Data Fundamentals DP-900](https://img.shields.io/badge/Microsoft-Azure_Data_Fundamentals_DP--900-0078D4?logo=microsoftazure&logoColor=white)

🏅 [Data Innovation Excellence Award, Dratech (2024)](https://dratech.org/patrick-okare-named-winner-of-the-dratech-data-innovation-excellence-award-2024/) · [Most Outstanding Data Engineering Professional of the Year, NITA (2021)](https://www.nigeriatechnologyawards.com/winners/individual-directory/)

---

### Stack

![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white) ![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD4?logo=delta&logoColor=white) ![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?logo=snowflake&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white) ![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-117865) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black)

Unity Catalog · Lakeflow Declarative Pipelines · Auto Loader · AUTO CDC · Azure Data Factory · Liquibase · Kimball dimensional modeling · Medallion architecture

---

### Featured: Helios Trading Lakehouse

Ten daily feeds from six depots (JSON, CSV, Parquet) through a medallion lakehouse on Unity Catalog. Auto Loader into Bronze, deduplication, CDC and SCD Type 2 in Silver, a Kimball star schema in Gold, then Metric Views, Genie and a Lakebase-backed operations app. Code and design docs: [databricks-dataml](https://github.com/patrickokare/databricks-dataml)

<p align="center"><img src="assets/helios-architecture.svg?v=2" alt="Helios Trading Lakehouse solution architecture: six depots and ten daily feeds land in a landing zone, flow through Bronze, Silver and Gold on Databricks with Unity Catalog, and serve Metric Views, Genie and a Lakebase operations app" width="100%"></p>

---

### Projects

| Project | What it shows |
|---|---|
| [databricks-dataml](https://github.com/patrickokare/databricks-dataml) | Databricks lakehouse portfolio: the Helios trading platform (complete) plus Formula 1, UK rail and video game sales builds in progress. Kimball models, incremental ELT, data quality checks |
| [EVLytics](https://github.com/patrickokare/evlytics-washington-portfolio-project) | Washington State EV registrations on Delta Lake and PySpark with Kimball modeling and medallion architecture |
| [spotify-lakehouse](https://github.com/patrickokare/spotify-lakehouse-portfolio-project) | Medallion lakehouse built from daily Spotify Web API batch ingestion, with data quality validation |
| [dbt-medallion-ecommerce-analytics](https://github.com/patrickokare/dbt-medallion-ecommerce-analytics) | Analytics-ready dbt models on Databricks |
| [citibikes-fabric](https://github.com/patrickokare/citibikes-fabric-portfolio-project) | Medallion architecture and dimensional model on Microsoft Fabric |
