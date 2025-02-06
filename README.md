# healthcare_dlt_pipeline
Healthcare Delta Live Table Pipeline with Medallion Architecture (Industrial Project)
Tech Stack - Databricks, PySpark, Delta Lake, Delta Live Table Job
      -> Setup notebook to create raw_diagnosis_mapping & raw_daily_patients delta table
      -> Ingest one time static data in raw_diagnosis_mapping from databricks volumes path
      -> raw_daily_patients delta table will keep on getting incremental data from mock PySpark job
      -> Setup notebook and add SQL declarative logics to create Bronze, Silver & Gold layer delta tables
      -> Create Delta Live Table pipeline job and add above notebook to create lineage among tasks
      -> Validate DLT Pipeline
      -> Run DLT pipeline in Development mode
