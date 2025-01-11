# ELT Pipeline - Showflake, Airflow and DBT

![image](https://github.com/user-attachments/assets/536f1a6b-7042-43ab-9019-f0d7f77a0f1e)


## Overview
A simple ELT pipeline using Snowflake, DBT, Astro, and Airflow to understand pipeline workflows.

## Technologies Used
- **Snowflake**: Data warehouse.
- **DBT**: Data transformation.
- **Airflow**: Pipeline orchestration.
- **Astro**: Airflow deployment management.

## Workflow
1. **Extract**: Load sample database into Snowflake.
2. **Load**: Raw data loaded into Snowflake.
3. **Transform**: Data transformed using DBT models and tests.
4. **Orchestrate**: Pipeline managed via Airflow.

## Key Features
- **DBT Tests**: Singular and generic tests for data validation.
- **Airflow DAG**: Manages task sequence in the pipeline.

## Installation
1. Clone repository.
2. Set up Snowflake and load the sample database.
3. Install DBT, Airflow, and Astro.
4. Configure DBT and Airflow.

## Running the Pipeline
1. Run DBT models: `dbt run`
2. Execute DBT tests: `dbt test`
3. Start Airflow: `airflow scheduler` & `airflow webserver`

## Conclusion
A foundational project to understand ELT pipeline components using modern data tools.

## License
MIT License - see [LICENSE](LICENSE).
