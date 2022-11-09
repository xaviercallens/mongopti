# MongoDB optimisation.

The repositry contains all the, notebooks and datasets that were used in the process of experimentation on MongoDB and its optimisation.

The total work is divided into three notebooks,

1. Data generation notebook - This notebook is used to connect to a MongoDB cluster and perform a particular, query on the collection available
for example, like the insert and filter query.

2. Training and Inference - This notebook contains machine learning experimentaion and the dataset has to be exported from the datasets folder and finally the machine learning model has to be saved.

3. Optimization - This notebook loads the saved machine learning model and then runs the optimisation process to find the best MongoDB cluster to run a query on a particular dataVolume.


## Requirements.

1). Python-3.6

2). Spark Mongo connector package- This has to be installed on the databricks cluster or locally to connect to the MongoDB.