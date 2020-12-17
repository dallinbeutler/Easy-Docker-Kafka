

start docker with an already configured instance of Zookeeper: `docker-compose up`

view a nice web front-end manager for Kafka go to:
`localhost:9000`

To run a simple consumer (prints anything it receives):

 `.\test-scripts\kafka_2.11-0.10.2.0\kafka_2.11-0.10.2.0\bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic kafka_test_topic`


to run simple producer (type anything and hit enter): 

`.\test-scripts\kafka_2.11-0.10.2.0\kafka_2.11-0.10.2.0\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic kafka_test_topic`
  
<br/>
<br/>
  
## thoughts:
Kafka Tool may be useful?

scripts you might be interested in are in:

`.\test-scripts\kafka_2.11-0.10.2.0\kafka_2.11-0.10.2.0\bin\windows`

(I did not create them)

tutorial I followed to get this far:
`https://zablo.net/blog/post/setup-apache-kafka-in-docker-on-windows/`

