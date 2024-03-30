# PySpark 
This project contain many mini projects written in Pyspark. Instead of learning Pyspark in Databricks, I wanted to experiment the hardship of not to have a new technology (Databricks). 
I believed my two dependencies' version (JAVA JDK or Hadoop winutils) were not incompatible to Pyspark version. It led to an impossibility to export an output to a designated folder as well as read all files inside a designated folder. There were some errors in the jupyter lab due to the incompatible versions.

Set up:
- JAVA JDK SE 8
- Python 3.10.0
- Pyspark 3.2.1
- Hadoop (winutils 3.2.1)
- Environment variables (JAVA_HOME, HADOOP_HOME, paths...)
- (And use cmd to navigate)

![image](https://github.com/britneydang/Learning-PySpark/assets/110323703/3ead39bb-1752-4b91-8407-88a5d7759f56)

In this project, I learn:
- how to set up my own local PySpark environment
![image](https://github.com/britneydang/Learning-PySpark/assets/110323703/6fbc315c-e66e-4a3e-8bc0-80ba5f4a6c0b)
- the Spark Architecture and Spark execution concepts
- the RDD (Resilient Distributed Datasets): include RDD Transformations and RDD Actiond
- the Spark DataFrame
