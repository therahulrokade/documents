**Kafka Steps:**

step 1: Download apache kafka
        https://kafka.apache.org/downloads

step 2: Extract the kafka Archive

step 3: Configure Environment Variables
        KAFKA_HOME --> C:\Software\kafka_3.8.0 (keep the kafka folder name shorten otherwise we will get The input line is too long error)

step 4: Edit config variables
        ** zookeeper.properties **
        dataDir=/tmp/zookeeper  -->  dataDir=C:/Software/kafka_3.8.0/zookeeper

        ** server.properties **
        log.dirs=/tmp/kafka-logs  -->  dataDir=C:/Software/kafka_3.8.0/kafka-logs

step 5: setup end

steps 6: for kafka next command please see the kafka_windows_readme.md file