

**https://www.safaribooksonline.com/library/view/artificial-intelligence-for/9781788472173/24275fed-e7db-4dc6-a5b9-f8fee8cf6d94.xhtml**

Spark MLlib provides two types of API included in the packages, namely spark.mllib  and spark.ml , where spark.mllib

is built on top of RDDs and spark.ml is built on top of the DataFrame. The primary machine learning API for Spark is now the DataFrame-based API in the spark.ml  package. Using spark.ml  with the DataFrame API is more versatile and flexible, and we can have the benefits provided by DataFrame, such as catalyst optimizer and spark.mllib , which is an RDD-based API that is expected to be removed in the future.





[**Spark for Data Science**](https://www.safaribooksonline.com/library/view/spark-for-data/9781785885655/ch06s02.html#)

 MLlib works in conjunction with the spark.ml package which provides a high level Pipeline API.

The fundamental difference between these two packages is that MLlib \(`spark.mllib`\) works on top of RDDs whereas the ML \(

`spark.ml`\) package works on top of DataFrames and supports ML Pipeline. Currently, both packages are supported by Spark but it is recommended to use the `spark.ml` package.





