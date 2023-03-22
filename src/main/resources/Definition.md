### Kafka
- Kafka is a open source distributed event streaming platform used by thousands of companies for high-performance data pipelines ,streaming analytics,data integration 
- kafka is falunt tolerant
- kafka has a cluster within we have kafka brokers
## Zookeeper
- zookeeper is used to manage the states of kafka brokers
## Kafka-Broker
- kafka broker is kafka server which acts as a mediator between producer and consumer
- In the production by default we have 3 kafka brokers
- Kafka brokers have multiple topics these topics are like categorizes
- within the topics we have multiple paritions 
## Producer
- producer produces the data ,data may be any form events,streams,json format .
- producer dont send the data directly to consumer instead send to kafka broker
## Consumer
- consumer consumes the data from broker
## offset
- offset is a sequence of id assigned to paritions which are unique and starts from 0