# setup-spark-locally
## What to expect at the end of this setup
1. Spark should be locally set up.
2. Be able to start spark shell in local mode.
3. Be able to start spark shell in yarn mode.

## prerequisites 
1. java 1.8 is installed (a tip: manage ur java versions using https://albertattard.github.io/java-boot-camp/docs/primer/sdkman/)
2. scala is installed `brew install scala`
3. Hadoop local setup should completed to ensure its( daemons like Namenode, Resources Manager etc) are running.
4. For yarn mode : in .bash_profile or .zshrc
`export HADOOP_CONF_DIR=/Users/<YOUR USER>/hadoop-2.7.7/etc/hadoop` 
OR 
`YARN_CONF_DIR=/Users/<YOUR USER>/hadoop-2.7.7/etc/hadoop`
 
## spark in shell mode
`spark-shell --master local`

## spark in yarn mode
`spark-shell --master yarn`

Official docs : https://spark.apache.org/docs/2.2.1/running-on-yarn.html 
