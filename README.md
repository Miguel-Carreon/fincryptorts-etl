# fincrypto-etl

This is a self-contained ETL pipeline, that transforms real time tiker data into usable finantial and crypto analytics data.


## After cloning the repo

Be sure to create a `.env` file identical to `.env.example`, and replace the values of the `MINIO_ROOT_USER` and `MINIO_ROOT_PASSWORD` keys for your respective local credentials. The docker compose file uses those keys as placeholders for the MinIO UI access control user and password respectively.