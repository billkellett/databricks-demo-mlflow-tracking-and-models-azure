# databricks-demo-mlflow-tracking-and-models-azure

This demo shows how to train a model, track it with MLflow, and deploy it with MLflow into Azure ML.  Naturally, it will only run on an Azure Databricks instance.

To install and run this demo in your own Databricks environment:

1. Import the two notebooks from the following URLs:

- https://github.com/billkellett/databricks-demo-mlflow-tracking-and-models-azure/blob/master/notebooks/MLflow%20Models%20Part%201%20-%20Training%20and%20Tracking.dbc

- https://github.com/billkellett/databricks-demo-mlflow-tracking-and-models-azure/blob/master/notebooks/MLflow%20Models%20Part%202%20-%20Serving%20with%20Azure%20ML.dbc

2. The Step 1 notebook shows how to use MLflow Tracking while building a scikit-learn model.  You must run the Step 1 notebook at least once.

3. The Step 2 notebook shows how to use MLflow Models to deploy a model into Azure ML.  You may run the Step 2 notebook as many times as you want, if you have run the Step 1 notebook at least once.
