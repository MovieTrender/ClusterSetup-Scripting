## Read [Project Documentation](https://github.com/MovieTrender/Documentation "Project Documentation")

##Cluster Setup & Scripting

Steps for setup a Hadoop cluster and scripts for executing different layers of MovieTrender.


###Tweet Downloader

Setup for installing [Tweet Layer](https://github.com/MovieTrender/TwitterLayer "Tweet Layer") in the cluster.

###HDFS

Steps for installing [HDFS Uploader](https://github.com/MovieTrender/HDFSUploader "HDFS Uploader") in the cluster.

###Train Mahout

Steps for training Mahout naives bayes ([Mahout](https://mahout.apache.org/ "Mahout")) and get the [Sentiment Model](https://github.com/MovieTrender/SentimentModel "Sentiment Model").

The data set used for training and test are tweets downloaded from Twitter.

###Impala load

Steps for loading data from HDFS to impala and setup the data model.

###Impala Analytics

Steps and queries for extracting tweets analytics from Impala.


###Infrastructure

The infrastructure used is a cluster in [Amazon Web Services](http://aws.amazon.com/ "Amazon Web Services") composed by three instances of m1.xlarge ([Instances in ec2](https://aws.amazon.com/ec2/instance-types/ "Instances in ec2")).





