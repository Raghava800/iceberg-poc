Project: Apache Iceberg with PySpark (Local Data Lake POC)

Designed and implemented an end-to-end Apache Iceberg data lake using PySpark to understand modern table formats and data reliability concepts.

Configured Spark + Iceberg using Hadoop catalog on local filesystem (Windows).

Created and managed Iceberg tables using Spark SQL and DataFrameWriterV2.

Implemented schema evolution (ADD COLUMN) without using mergeSchema=true.

Appended data with strict schema validation and safe writes.

Simulated accidental overwrite scenarios and recovered data using Iceberg time travel (snapshots).

Queried Iceberg metadata tables (snapshots, history, files) for audit and debugging.

Demonstrated why direct Parquet reads are not supported for Iceberg-managed tables.

Compared Parquet vs Iceberg behavior for file creation, schema management, and recovery.

Tech Stack: PySpark, Apache Iceberg, Spark SQL, Hadoop Catalog, Parquet
