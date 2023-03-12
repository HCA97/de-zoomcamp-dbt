
## Local Setup

1. Install Pacakages
    ```bash
    pip install 'piperider[bigquery]'
    pip install dbt-core dbt-bigquery
    ```
2. Initialize Repo
    ```bash
    dbt init
    dbt deps
    dbt build --vars "{'is_test_run': false}"
    piperider init
    piperider run
    ```
3. Check the dashboards.