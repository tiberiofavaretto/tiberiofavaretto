# Tiberio Favaretto

Data Engineer at Deloitte, working mostly in the Microsoft data stack — **Microsoft Fabric**,
**Azure** (Data Factory, Synapse) and **Azure Databricks**. Day to day I build medallion lakehouses,
ETL/ELT pipelines and semantic models. On the side I write small tools that solve the annoyances I
run into while doing it.

I also cover the NFL for Huddle Magazine, which is why some of my projects use football data.

### Tools I've built

- **[fabric-notebook-dependency-mapper](https://github.com/tiberiofavaretto/fabric-notebook-dependency-mapper)**
  — reads a folder of Spark/Fabric notebooks, works out which tables each one reads and writes, and
  builds the execution DAG (the order to run them in). It grew out of a metadata-driven orchestration
  setup I put together at work; this is a clean, generic version of the idea.
- **[sql-schema-sync](https://github.com/tiberiofavaretto/sql-schema-sync)**
  — compares a source and a destination table and generates (or applies) the `ALTER` statements to
  reconcile schema drift: add, drop and retype columns. Runs locally on DuckDB.

### Data platform projects

- **[nfl-stats-dbt](https://github.com/tiberiofavaretto/nfl-stats-dbt)**
  — analytics engineering with dbt on NFL data: staging → marts, tests, docs and CI. Runs on DuckDB.
- **[fabric-retail-analytics](https://github.com/tiberiofavaretto/fabric-retail-analytics)**
  — an end-to-end Microsoft Fabric solution: PySpark notebooks, a Data Pipeline, a Gold star schema
  and a Power BI semantic model.

### Working with

Microsoft Fabric · Azure Data Factory · Azure Synapse · ADLS Gen2 · Azure Databricks · PySpark &
Spark SQL · Delta Lake · dbt · Power BI · Python · SQL

### Elsewhere

- LinkedIn: [linkedin.com/in/tiberiofavaretto](https://www.linkedin.com/in/tiberiofavaretto/)

<!-- This file lives in a repo named exactly "tiberiofavaretto", so GitHub shows it on my profile. -->
