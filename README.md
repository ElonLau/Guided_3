# Guided_3

Now that you’ve preprocessed the incoming data from the exchange, you need to create the
final data format to store on the cloud. The cloud will also store historic exchange data, so
Spring Capital can look up any trading day and easily find historic data.
This preprocessed data will be used in the following ETL process, as well as for adhoc user
queries. <br/>
At the end of the last step, you have created three partitions under output_dir. It’s easy to go
through them one by one and create corresponding datasets. Note that the target dataset
should have the specific schema required by the partition. <br/>
<br/>
Learning Objectives:
By the end of this step, you will be able to…
- Create Spark DataFrames using Parquet files
- Perform data cleaning using Spark aggregation methods.
- Use cloud storage as output of Spark jobs.
<br/>
<br/>
- Setup
'End-of-Day_Data_Load_Notebook' has the Pyspark code to work on the raw preprocessed parquet files, apply correction and save it back to Azure storage

Also, the detailed steps and screenshots are in the document 'End-of-Day Data Load Screenshot'
