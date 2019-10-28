---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 5 Sec 40 V2         <br/>
**Topic**: Spark <br/>
**Amount of time**: 60 minutes <br/>
**Author**: Alison Peebles

Adapted from the DS Lesson Starters repository.

***

#### Lesson Summary:

This lesson introduces Spark and takes a look at implementing Machine Learning models via pyspar. The lesson starts with a discussion of what Spark is and some of the history behind the project. From there, implementing machine learning models is investigated for a classification tasks. The latter of these incorporates student code practice. Finally, students compare the models they build with the PySpark API and select the best one.

#### Topic:

Spark

#### Learning goals for this lesson:

* Students will be able to implement a supervised learning model using pyspark
* Students will be able to explain HDFS and Spark
* Students will be able to explain the relationships between Hadoop, Spark, and Databricks
* Students will be able to differentiate between Spark RDDs and Spark Dataframes and when each is appropriate
* Students will be able to locate and explore the Spark.ML documentation
* Students will be able to  code along a text classification problem using four different ml algorithms, a data prep pipeline, and gridsearch to fine tune a model
#### Prerequisite knowledge:

* Students should have previous knowledge implementing supervised learning models using scikit-learn

#### Prequisite Learn-Materials:

* [Introduction to Big Data](https://github.com/learn-co-curriculum/dsc-big-data-introduction)
* [Parallel and Distributed Computing with Map-Reduce](https://github.com/learn-co-curriculum/dsc-parallel-and-distributed-computing-with-mapreduce)
* [Big Data Analytics on Apache Spark](https://github.com/learn-co-curriculum/dsc-big-data-analytics-apache-spark)
* [Installing and Configuring PySpark with Docker](https://github.com/learn-co-curriculum/dsc-spark-docker-installation)
* [Understanding Spark Context - Lab](https://github.com/learn-co-curriculum/dsc-sparkcontext-lab)
* [Machine Learning with Spark](https://github.com/learn-co-curriculum/dsc-machine-learning-with-spark)

#### Post Learn-Materials:

* [Resilient Distributed Datasets (RDDs) - Lab](https://github.com/learn-co-curriculum/dsc-resilient-distributed-datasets-rdd-lab)
* [Word Count with Map-Reduce - Lab](https://github.com/learn-co-curriculum/dsc-word-count-with-map-reduce-lab)
* [Machine Learning with Spark -  Lab](https://github.com/learn-co-curriculum/dsc-machine-learning-with-spark-lab)

#### Relevant learning goals from Airtable: 

*  SPARK.1.rec8XkzG9FZE1H4ch
*  SPARK.1.rec8bMxOodWcLwlQm
*  SPARK.1.recDGvR737mDpPjjI
*  SPARK.1.recFdqU7VhLkeLcmL
*  SPARK.1.recPNXJ4TcYmTDCjI
*  SPARK.1.recQBVxz91dA7IIJw
*  SPARK.1.recQCvh5Gro3UPjSO
*  SPARK.1.recSixAoaZ35bKTvF
*  SPARK.1.recaJpr0j4QQ2mwbJ
*  SPARK.1.recpcfkNNXlKP7bwk
*  SPARK.1.recqKGgnhtAxbjhLP
*  SPARK.1.recvqjUUHQVK8oy1T
*  SPARK.2.rec2o5acQfjN57NpD
*  SPARK.2.recAc4HFURfQbivxO
*  SPARK.2.recB18IOuQ7uShPkj
*  SPARK.2.recGFDXQDtftexD4y
*  SPARK.2.recPicZM55j3Rm3qQ
*  SPARK.2.recR7Oz95a4V0ajX5
*  SPARK.2.recS5VgaH2SWaJMMc
*  SPARK.2.recUQ2cmhmHpYyoaL
*  SPARK.2.recUtIZLA4eYJMDJh
*  SPARK.2.reca1KxGmtECirS0d
*  SPARK.2.recqfSvKEN3Y7yc1e
*  SPARK.2.recrOklniYazeO921
*  SPARK.2.recrOklniYazeO921
*  SPARK.3.recZsPfe1Tw4aYxVc
*  SPARK.3.recsXdLnKK6KE5dMD
*  SPARK.3.recsXdLnKK6KE5dMD

#### Materials

* Ipython notebook

#### Vocab / Concepts 

* HDFS
* YARN


#### Lesson Outline:

* Spark Background
	* HDFS
	* YARN
	* History of Spark
	* Spark APIs
* Using PySpark
* Classifying with Spark
* Choosing a Classifier
