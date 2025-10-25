kafka version : kafka_2.13-3.8.0
Java version 17
Spring boot version 3.5.6
Start kafka server --> kafka/bin/kafka-server-start.bat
start Zookeeper kafka/bin/zookeeper-server-start.bat
Start spring boot app.
download offsetexplorer_64bit and add your kafka topic. I used "entitlement" as my topic id and boot strap server host is 9092.
ex in properties : spring.kafka.bootstrap-server=localhost:9092
