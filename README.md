# Requirements

- To ingest and process CSV file with two columns; dining place name, dining hour
- To create a self service dashboard where one can ask question about the datasets

# Simple Architecture

- Voila will serve as app running on Binder
- Use modin / fugusql to query and process DuckDB
- User can choose to export, init the database as a file
