## 👋 Welcome! My name is Ryan Espinal

## 📜 About me
Data analyst with 5 years of experience in healthcare data, automating workflows with Python and SQL across BigQuery. Working towards shifting into the data engineering space by leveraging my analytical understanding of downstream data to build meaningful data pipelines and architecture. "Curiosity killed the cat, but Satisfaction brought it back". I am simply interested in the challenges associated with the data industry as a whole.

## ⚒️ Languages and Systems
- **Languages:** Python, SQL (PostgreSQL), Bash
  - **Libraries:** Request, Pandas, NumPy
- **Data & Cloud:** BigQuery, AWS S3, SFTP, REST API, Apache Airflow
- **Data Workflows:** Data Extraction & Transformation, Workflow Automation, Data Validation & QA, Source Data Documentation, SOP Development
- **Healthcare Data:** Drug NDCs, Diagnosis ICD-10 Codes, Procedure CPT Codes, HCP Cohort Data 
- **IDEs:** Google Colab, VSCode, Jupyter Notebook
- **DevOps:** Git, Docker
- **Tools:** Excel, FileZilla, Looker

## 💼 Experiences
- **Business Workflow**
  - Curating business SOP to streamline workflows and communication between varied teams.
- **Handling Big Data**
  - Building and maintaining business-critical SQL queries utilizing window functions, nested queries, and dependency variables.
- **Business Requirements**
  - Reviewing source documentation and field definitions and sharing findings in recurring meetings about downstream data usage.
  - Building shareable scripts and excel functions reducing tedious tasks to improve productivity workflows.
- **Data Analysis**
  -  Transforming raw data into clear insights through cleaning and preprocessing.
- **Healthcare Data Analysis**
  - Understanding of healthcare claim and patient data to generate impactful audiences for marketing team based on client needs and focus.
- **Data Engineering Initiative**
  - Working on building, orchestrating, and documenting my personal automated ETL/ELT pipeline project to portray my full understanding of what an end-to-end data pipeline requires.
- **Leveraging APIs**
  - Reviewing documentations and ingesting source data from various sources APIs for business needs.
 
 ## 🏗️ End-to-End Pipeline Project
 🎵 [Music Pipeline Project](https://github.com/respinar1/music-pipeline)

Music has always interest me and I have always wondered how music carries influence between cultures, not just domestically but also globally, such as American Pop's influence on J-Pop. This project is intended to join my interest of both music and data, and demonstrate my developing data engineering skillset. 

- **Project Goal:** Build an end-to-end ETL pipeline in Python and SQL to compare genre popularity and overlap across geographical regions, using artist and tag metadata from the MusicBrainz REST API.
- **Built so far:** Docker Compose environment (Python ingestion and PostgreSQL containters, persistent volume, bind-mounted scripts), credential kept out of version control, API client built to meet the source's rate-limit and User-Agent requirements, structured error logging with re-raised expectaions, and a decision log documenting each architectural choice.
- **Planned:** dbt models (Medallion Method) with uniqueness, null, and referential integrity test; Airflow orchestration with retires, failure alerts, and backfill; migration to BigQuery with partitioning; a dashboard of regional genre trends.
