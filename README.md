<div align="center">

<br>

# ✦ &nbsp; Rajan Gajjar &nbsp; ✦

<sub><sup>Data Engineer &nbsp;·&nbsp; Pipeline Architect &nbsp;·&nbsp; Cloud Native</sup></sub>

<br>

</div>

<br>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3500&pause=1200&color=c9b8f0&center=true&vCenter=true&repeat=true&width=580&height=45&lines=Building+scalable+data+pipelines+from+scratch;ETL+%2F+ELT+%7C+Medallion+Architecture+%7C+Cloud+DWH;Snowflake+%C2%B7+Airflow+%C2%B7+dbt+%C2%B7+Spark+%C2%B7+AWS)](https://git.io/typing-svg)

</div>

<br>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rajan%20Gajjar-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com)
&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-rajangajjar1402-c5221f?style=flat-square&logo=gmail&logoColor=white)](mailto:rajangajjar1402@gmail.com)
&nbsp;
[![Oracle](https://img.shields.io/badge/Oracle%20Certified-Analytics%20Cloud%202025-c74634?style=flat-square&logo=oracle&logoColor=white)](https://linkedin.com)
&nbsp;
</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/Open%20to%20Work-Data%20Engineering%20Roles-2e7d32?style=flat-square&logo=checkmarx&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/Location-Ahmedabad%2C%20India-3d2b6b?style=flat-square&logo=google-maps&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/Best%20Performer-Q3%202025%20%F0%9F%8F%85-5b21b6?style=flat-square" />
</div>

---

<img align="right" alt="Data Engineering" width="380" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

## `$ whoami`

```yaml
Name      : Rajan Gajjar
Role      : Data Engineer
Company   : TELUS Digital  🏅 Best Performer Q3 2025
Location  : Ahmedabad, India 🇮🇳
Focus     :
  - Scalable ETL/ELT Pipeline Design
  - Cloud Data Warehousing (Snowflake, AWS)
  - Real-Time Streaming (Kafka, Spark)
  - Medallion Architecture (Bronze→Silver→Gold)
  - Data Quality & Governance Engineering
Philosophy: "Data without pipelines is just noise."
Status    : Open to exciting Data Engineering roles 🟢
```

<br clear="right"/>

---

## ⚙️ Tech Arsenal

<div align="center">

| Category | Technologies |
|:---:|:---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) |
| **Orchestration** | ![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white) ![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apache-spark&logoColor=white) ![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white) |
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white) ![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white) ![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white) ![Glue](https://img.shields.io/badge/Glue-8B6914?style=flat-square&logo=amazon-aws&logoColor=white) |
| **Warehousing** | ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&logo=amazon-redshift&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) |
| **Transform** | ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **Viz** | ![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=power-bi&logoColor=black) |

</div>

---

## 🏗️ Architecture Signature

```
╔══════════════════════════════════════════════════════════════════╗
║            MEDALLION DATA LAKEHOUSE  (My Specialty)             ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  📥 SOURCES         🔄 PROCESS          🏛️ SERVE                ║
║  ─────────          ─────────           ──────                   ║
║  REST APIs    ──►   🥉 BRONZE           Snowflake / Redshift     ║
║  S3 / Files   ──►   (Raw Ingest)   ──►  ──────────────────────   ║
║  PostgreSQL   ──►   🥈 SILVER           Power BI Dashboards      ║
║  Kafka Events ──►   (Validated)    ──►  ──────────────────────   ║
║               ──►   🥇 GOLD             Analytics / ML Ready     ║
║                     (Aggregated)                                 ║
║                                                                  ║
║  Orchestration: Apache Airflow  │  Transform: dbt + PySpark      ║
║  Quality: 35% fewer defects     │  Docker Compose Containerised  ║
╚══════════════════════════════════════════════════════════════════╝
```

---

## 🚀 Featured Projects

<div align="center">

### 🛒 E-Commerce Analytics Pipeline
**`Python`** · **`Apache Airflow`** · **`PostgreSQL`** · **`Docker`** · **`REST APIs`**

</div>

> Production-style end-to-end pipeline extracting data from Fake Store REST API. Fully containerised via Docker Compose with Airflow orchestration, branching logic, XCom, retries, and incremental loading into PostgreSQL staging schema.

```
FakeStore API → Airflow DAG → Python/Pandas Transform → PostgreSQL → Analytics Layer
                  (XCom + Branching + Retries)       (Incremental)
```

---

<div align="center">

### 🏠 Airbnb End-to-End Medallion Pipeline
**`Snowflake`** · **`dbt`** · **`AWS S3`** · **`Python`** · **`SQL`**

</div>

> Full medallion architecture on Snowflake using dbt — incremental models, SCD Type 2 snapshots, Jinja-templated One Big Table, custom macros, automated schema separation, and complete lineage via dbt docs.

```
AWS S3 ──► Snowflake Staging
              │
              ├──► 🥉 BRONZE (raw)
              ├──► 🥈 SILVER (validated + SCD Type 2)
              └──► 🥇 GOLD  (aggregated OBT + dbt docs)
```

---

<div align="center">

### 📊 Sales & Operations Performance Analysis
**`Python`** · **`SQL`** · **`PostgreSQL`** · **`Power BI`** · **`Pandas`**

</div>

> End-to-end diagnostic analysis on large-scale sales data with cohort analysis, statistical aggregations, and interactive Power BI dashboards — **cut manual reporting effort by 40%**.

---

## 💼 Experience Timeline

```
2025 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
    ▶ TELUS Digital — Data Operations Analyst (Data Eng.)
      📍 Ahmedabad  |  Jul 2025 – Present  |  🏅 Best Performer Q3 2025
       ✦ Built automated Python ETL pipelines (REST APIs + PostgreSQL + flat files)
       ✦ Reduced data defects by 35% via quality engineering controls
       ✦ End-to-end data lineage mapping for governance & compliance
       ✦ Structured logging + observability for production pipeline MTTR

2024 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
    ▶ Skyward Techno Solution — Data Engineer Intern
      📍 Ahmedabad  |  Jan 2024 – May 2024
       ✦ ETL workflows: Python + SQL → Excel/flat files/PostgreSQL
       ✦ Star schema dimensional modelling for data warehouse
       ✦ Power BI dashboards for KPI & campaign monitoring
```

---

## 🎓 Education & Certifications

<table align="center">
<tr>
<td width="50%" valign="top">

**🎓 Education**

**B.E. Information Technology** · CGPA: 7.93
SAL College of Engineering · 2021–2024

**Diploma in Mechanical Engineering** · CGPA: 8.15
R.C. Technical Institute · 2018–2021

</td>
<td width="50%" valign="top">

**📜 Certifications**

🏆 **Oracle Certified Professional** – Analytics Cloud 2025

📊 **Data Analyst Bootcamp** – Udemy

🐍 **Python Programming** – KICT

💻 **Multilingual Computer Programming** – CDAC

</td>
</tr>
</table>

---

<div align="center">

### 🤝 Let's Build Something Remarkable

*I turn complex, messy data into clean, scalable, analytics-ready pipelines.*
*If you're working on a challenging data problem — let's talk.*

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Send_a_Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rajangajjar1402@gmail.com)

<br>

> *"In God we trust; all others must bring data."* — W. Edwards Deming

<br>

<br>

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     Let's build something remarkable.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>
