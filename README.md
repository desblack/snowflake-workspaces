# snowflake-workspaces
This repo demonstrates how to build a data pipeline to populate a simple dimensional data mart using Snowflake Workspaces integrated with Git.

The data is sourced from the SNOWFLAKE_SAMPLE_DATA.TPCH_SF1 schema. The data pipeline transforms the data in several steps:

1. extract the data as views
2. stage the data as tables and merge from views
3. create a simple dimensional data mart as dynamic tables
