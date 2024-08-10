** windows kafka steps **

step 1: start zookeeper
        .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

step 2: start a kafka broker
        .\bin\windows\kafka-server-start.bat .\config\server.properties

step 3: checking kafka and zookeeper services up and running
        jps --> type in cmd