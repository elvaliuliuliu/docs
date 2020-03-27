### Concepts
-	Will .NET for Apache Spark support be added directly in Databricks?
 
 There is no out-of-box experience currently. You can [deploy your app to the cloud through Azure Databricks](https://docs.microsoft.com/en-us/dotnet/spark/tutorials/databricks-deployment) and [submit your app through `spark-submit` and Apache Livy](https://docs.microsoft.com/en-us/dotnet/spark/how-to-guides/hdinsight-deploy-methods).
-	Provide some customer/team cases where they have adopted .NET for Spark and successfully productionalized their pipelines.
 
 Office 365 => Brigit
-	Does it support Spark Streaming?

Yes, it supports [Structured Streaming with .NET for Apache Spark](https://docs.microsoft.com/en-us/dotnet/spark/tutorials/streaming).
-	Does it support Delta Lake? How does it handle Delta Lake when it is running in Databricks vs when it is running on the OSS version of Delta Lake?

Yes, Delta Lake is supported. => Andrew

###	How-to guides
- What's the work around when broadcast is not supported? (Use static variables, Document this until Broadcast is supported)

=> Niharika
-	How to access S3 (read the data from S3)?

-	How to read text files (different formats) in .NET for Apache Spark and transfer the raw data into readable format?

=> Get this into a blog
-	How do I deploy .NET for Spark in different clusters such as Databricks, AWS, Synapse, HDInsight and my own Spark Cluster?

Please refer to the below documentaion on how to deploy .NET for Spark in different clusters:
   - [Deploy to Databricks](https://docs.microsoft.com/en-us/dotnet/spark/tutorials/databricks-deployment)
   - [Deploy to AWS EMR Spark](https://docs.microsoft.com/en-us/dotnet/spark/tutorials/amazon-emr-spark-deployment)
   - [Deploy to Azure HDInsight](https://docs.microsoft.com/en-us/dotnet/spark/tutorials/hdinsight-deployment)
-	How do I do streaming with XYZ where XYZ is Kafka, Eventhub?

Please refer to the below documentation on how to do streaming:
- [Kafka example](https://docs.microsoft.com/en-us/dotnet/spark/tutorials/streaming)
- Eventhub => Jose
- How do I use .NET for Apache Spark directly in Databricks notebooks?

Is this supported currently? I don't think so => need to confirm with Terry
