# Working with Parquet Data in Spark

## Parquet Background
[Explanation by Twitter](https://blog.twitter.com/2013/dremel-made-simple-with-parquet)
[Spark+Parquet Sample](http://zenfractal.com/2013/08/21/a-powerful-big-data-trio/)
[Parquet Performance[(http://hadoopified.wordpress.com/2013/10/18/parquet-columnar-storage-hadoop/)
[Predicate Pushdown](https://github.com/JacobMetcalf/parquet-mr/commit/5f0f929e42c9a0a8cf3a7bf418a252aa7e4a1168)

## Contributing
Some helpful links related to Spark-Parquet integration.

### Relevant Codebases
[parquet-mr](https://github.com/Parquet/parquet-mr)

### Relevant Snippets
[Parquet Writer example](http://php.sabscape.com/blog/?p=623)
[SparkContext::newAPIHadoopFile](https://github.com/apache/incubator-spark/blob/master/core/src/main/scala/org/apache/spark/SparkContext.scala)
[RDD::saveAsHadoopFile](https://github.com/apache/incubator-spark/blob/master/core/src/main/scala/org/apache/spark/rdd/PairRDDFunctions.scala)
[RDD::saveAsSequenceFile](https://github.com/apache/incubator-spark/blob/master/core/src/main/scala/org/apache/spark/rdd/SequenceFileRDDFunctions.scala)
[MLUtils::loadLabeledData](https://github.com/apache/incubator-spark/blob/master/mllib/src/main/scala/org/apache/spark/mllib/util/MLUtils.scala)
[Avro Projection](https://github.com/Parquet/parquet-mr/blob/master/parquet-avro/src/test/java/parquet/avro/TestSpecificInputOutputFormat.java)
[MLI load functions](https://github.com/amplab/MLI/blob/master/src/main/scala/interface/MLContext.scala)
