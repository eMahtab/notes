# Kafka


## Kafka Overview :

!["Apache Kafka Overview"](images/kafka_overview.png?raw=true)


## Order of consumption of messages in a topic
As a topic is divided into multiple partitions, by default the order of message processing is not guaranteed. But if you want to guarantee order of message processing, you can just use one partition for the topic (which would reduce the processing speed), or use Custom partition key such that all messages for the specific event or user, land to the same partition.
