# population-etl-pipeline
To build an ETL pipeline that downloads Malaysia population data from DOSM, validates it, loads it into SQL Server, and prepares it for reporting.

Tech Stack:
1.Pentaho PDI
2.SQL Server (Express pun cukup)
3.GitHub
4.Power BI (later)
5.DOSM Open Data

Folder Structure:
population-etl-pipeline
│
├── README.md
│
├── docs/
│   ├── architecture.drawio
│   ├── architecture.png
│   ├── implementation.md
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── sample/
│
├── pentaho/
│   ├── transformation/
│   └── jobs/
│
├── sql/
│   ├── create_table.sql
│   ├── staging.sql
│   ├── validation.sql
│   └── indexes.sql
│
├── screenshots/
│
└── powerbi/
