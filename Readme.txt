# Summmary


<p>
This project focus on Resilient Distributed Datasets or RDDs of the open-source engine Apache Spark developed specifically for handling large-scale data processing and analytics. RDDs are the unique native core data structure of Apache Spark, which allows to process data on numerous remote worker machines.
RDDs are partioned and distributed on the nodes in the Spark cluster.
The RDDs are resilient and are retrieved from the data existing in other nodes  even when processes are crashing or nodes are failing .
</p>
<p>
According to the 
<a href="https://spark.apache.org/docs/0.8.1/api/core/org/apache/spark/rdd/RDD.html" target="_blank">documentation</a> 
a Resilient Distributed Dataset (RDD), the basic abstraction in Spark. Represents an immutable, partitioned collection of elements that can be operated on in parallel. This class contains the basic operations available on all RDDs, such as map, filter, and persist. In addition, PairRDDFunctions contains operations available only on RDDs of key-value pairs, such as groupByKey and join
<p>
    
<p>
There are two types of data sets used here. Numeric data created from random data and the breast cancer data set, and string data randomly choosen from text of the internet. RDD operations are carried out on all data sets. For example a word count is made for the the text data to get the 10 most frequent words.
</p>

<p>Among many others the following tasks are carried out:</p> 
        
<ul>
  <li>Import packages</li>
  <li>Inspect SparkContext</li>
  <li>Lambda functions</li>    
  <li>Creating RDDs by using schemas and parallelize</li>
  <li>Selecting data from RDDs</li>
  <li>RDD operations</li>  
  <li>Creating a dictionary of word counts</li>
  <li>Creating a list of top ten words</li>
  <li>Using stopwords to filter the text</li>
</ul>     
    
    
<p>
<h2>Spark system architecture</h2>
</p> 



<img src="spark_achitecture.png" alt="Smiley face" align="left"  style="margin-left: 0px; margin-right: 0px; margin-top: 20px; margin-bottom: 20px; float: left; width: 800px; height: 300px"> 


<p>
This Jupyter notebook is made for running on a local machine, but a similar notebook was conducted on cluster provided by Databricks. Similar offerings with notebook integration
are offered by a lot of suppliers.
</p> 
