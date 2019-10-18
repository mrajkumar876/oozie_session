Problem 1:

Execute this command from ambari-qa user:

spark-submit --master yarn --deploy-mode cluster  --class org.apache.spark.examples.sql.hive.HiveFromSpark --jars /usr/hdp/current/spark-client/lib/datanucleus-rdbms-3.2.9.jar,/usr/hdp/current/spark-client/lib/datanucleus-core-3.2.10.jar,/usr/hdp/current/spark-client/lib/datanucleus-api-jdo-3.2.6.jar /usr/hdp/current/spark-client/lib/spark-examples-1.6.3.2.6.5.0-292-hadoop2.7.3.2.6.5.0-292.jar 

Find out the issues and fix them.


Problem 2:

