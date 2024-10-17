**Problem Statement: Implementing Change Data Capture (CDC) Using Full Load with Azure Data Factory (ADF) and Snowflake**

In this challenge, your task is to implement a Change Data Capture (CDC) solution using a full load approach. You will be provided with access to Azure Data Factory (ADF) and necessary credentials. The goal is to create an end-to-end pipeline that captures changes from a data source and loads them into a target table in Snowflake.

### Requirements:
1. **Set up Azure Data Factory (ADF)**: Utilize the provided credentials to configure ADF. This will serve as the primary orchestration tool to implement the CDC process.
2. **Create a Snowflake Community Edition Account**: If you don’t already have one, create a Snowflake Community Edition account. Snowflake will be the destination for the data ingested via CDC.
3. **Implement the CDC Pipeline**:
   - Design an ADF pipeline that pulls data from the source and performs a full load for CDC.
   - Ensure the pipeline identifies and processes changes (inserts, updates, and deletes) in one specific table from the source.
   - Load the transformed data into the corresponding table in Snowflake, maintaining data integrity.
4. **Connect ADF with Snowflake**: Establish a connection between ADF and Snowflake for data transfer. You may need to use Snowflake connectors or linked services within ADF.

### Deliverables:
- A fully functional ADF pipeline that implements CDC for a single table.
- Documentation on how the solution was built, including steps to replicate the setup.
- Any relevant testing results to verify the CDC functionality.

**Bonus**: Optimize the pipeline to reduce data processing time and enhance performance.
