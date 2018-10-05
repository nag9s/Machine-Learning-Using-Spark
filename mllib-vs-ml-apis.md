 Spark MLlib provides two types of API included in the packages, namely spark.mllib  and spark.ml , where spark.mllib

 is built on top of RDDs and spark.ml is built on top of the DataFrame. The primary machine learning API for Spark is now the DataFrame-based API in the spark.ml  package. Using spark.ml  with the DataFrame API is more versatile and flexible, and we can have the benefits provided by DataFrame, such as catalyst optimizer and spark.mllib , which is an RDD-based API that is expected to be removed in the future.

