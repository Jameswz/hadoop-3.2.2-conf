# hadoop-3.2.2-conf

The configuration files are for hadoop 3.2.2 pseudo distributed mode setup with access permission disabled.

1. Download all xml files to replace existing hadoop configuration files in $HADOOP_HOME/etc/hadoop

2. Set ENV for Hadoop :

	export HADOOP_HOME=/home/username/hadoop-3.2.2  (Replace by your hadoop location)

	export HADOOP_INSTALL=$HADOOP_HOME

	export HADOOP_MAPRED=$HADOOP_HOME

	export HADOOP_COMMON_HOME=$HADOOP_HOME

	export HADOOP_HDFS_HOME=$HADOOP_HOME

	export YARN_HOME=$HADOOP_HOME

	export HADOOP_COMMON_LIB_NATIVE_DIR=$HADOOP_HOME/lib/native

	export PATH=$PATH:$HADOOP_HOME/bin:$HADOPP_HOME/sbin


