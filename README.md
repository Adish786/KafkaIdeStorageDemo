First set the KAFKA_HOME with cmd or setx KAFKA_HOME C:/Program Files/confluent-7.7.1
Add the plugin in intliji ide                 Batch Scripts Support
confluent-7.7.1/etc/kafka/zookeeper.properties file add the location  dataDir=../tmp/zookeeper
confluent-7.7.1/etc/kafka/server-0.properties    create the number of broker file in that loaction and change the broker.id=0 and listeners=PLAINTEXT://:9092 and log.dirs=../tmp/kafka-logs-0
