### Assignment Details
dbt project to create model on the data loaded into snowflake database from source Postgres database using Hevodata pipeline.

### Directory Structure

  #### models
SQL models and schema files.

  #### tests
This folder contains tests to verify generated model table.
Tests are added for below categories
-- tests associated with the appropriate columns of model and their dataypes.
-- Data completness by verifying rows.
-- verification of expected values for the given datatypes.

 #### data
Dataset files loaded into source database tables.

### How to run and genereate model table
Run command `dbt run`

### How to tests to verify the generated model table
Run command `dbt test`

### Resources:
- #### DBT
Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- #### Snowflake
https://docs.snowflake.com/en/developer-guide/snowflake-cli-v2/connecting/connect

