# Data Engineering for Covid19 

- This repo contains the files for setting up a data ingestion pipeline for Covid19 tweets
- The tweets were collected from the streaming endpoint provided by Twitter. Through their developer program
- Following files are stored in this repo:
   1. Code for hydrating the tweet IDs (python)
   2. Code for taking snapshot of ES index (python)
   3. Code for basic input/output for ES domain (python)
   4. CloudFormation template for setting up Data Ingestion pipeline (yaml)
