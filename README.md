# Wine quality Prediction
 



import dagshub
dagshub.init(repo_owner='harshith007varma007', repo_name='Wine-quality-Prediction', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


import dagshub
dagshub.init(repo_owner='harshith007varma007', repo_name='Wine-quality-Prediction', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/harshith007varma007/Wine-quality-Prediction.mlflow

export MLFLOW_TRACKING_USERNAME=entbappy 

export MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0

```

730335587966.dkr.ecr.us-east-1.amazonaws.com/wine_quality