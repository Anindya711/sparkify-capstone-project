# sparkify-capstone-project
This is the capstone project,as part of this one churn prediction system is built using pyspark.

**Project Overview** \
In this project, we will use PySpark to predict if a customer will cancel the subscription or not for a online music streaming company
called Sparkify. This is a classification problem, as we will predict if a customer will churn or not. This is a pain area in all the
areas now a days, IT, Healthcare, Infrastructure etc.

**Project Motivation** \
Machine learning is critical to helping different organizations understand which messages are relevant to them and which messages to prioritize. Predicting churn rates is a challenging and common problem that data scientists and analysts regularly encounter in any customer-facing business. Additionally, the ability to efficiently manipulate large datasets with Spark is one of the highest-demand skills in the field of data. The full dataset is 12GB, of which we analyzed a mini subset of 123MB. We will use PySpark extensively to solve this problem.

**Steps** \
  Load large datasets into Spark and manipulate them using Spark SQL and Spark Dataframes.
  Use the machine learning APIs within Spark ML to build and tune models.
  
**Structure**\
The repository contains following folders.
>*1. data* - contains the mini sparkify dataset.\ **Note :Could not upload 123MB data due to github limit**.\
>*2. sparkify.ipynb* - Contains the analysis and detailed coding of the project.\
>*3. sparkify.html* - Contains the analysis and detailed coding of the project in a html format.\
>*4. readme.md* - Readme file.

**Pre-requisites** \
  Following packages should be installed in the system before running the notebook.
  >SparkContext
  >pyspark\
  >pyspark.sql.SparkSession\
  >pyspark.sql\
  >datetime\
  >numpy\
  >pandas\
  >matplotlib.pyplot\
  >sklearn
  >seaborn\
  >pyspark.ml
  
  **Blog**
  The analysis could be found at my blog link. 
  
  >https://medium.com/@anindya.prince/sparkify-churn-prediction-using-pyspark-36b853ab0f2a?source=friends_link&sk=a9af69cc0276773aac059012cb8f80ad
  

**References**

  >https://docs.databricks.com/spark/latest/mllib/binary-classification-mllib-pipelines.html
  >https://towardsdatascience.com/machine-learning-with-pyspark-and-mllib-solving-a-binary-classification-problem-96396065d2aa
  >https://spark.apache.org/docs/2.2.0/api/java/index.html?org/apache/spark/ml/evaluation/BinaryClassificationEvaluator.html
  >https://spark.apache.org/docs/2.1.0/ml-classification-regression.html#random-forest-classifier
