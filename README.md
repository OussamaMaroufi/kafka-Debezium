### Kafka Components:

- Kafka broker
- Kafka producer: produce content to kafka broker
- kafka consumer: Consume content from a broker
![image](https://github.com/OussamaMaroufi/kafka-Debezium/assets/93825558/44ce5a33-9904-4c5d-a7c0-b3e414a50c09)

- You can only append to kafka topic u cannot delete.
 ![image](https://github.com/OussamaMaroufi/kafka-Debezium/assets/93825558/a1618a88-2484-4382-aaa2-ec2bce7e4969)

- We can see that topic is going larger and larger ..😕 what we should do in that case.
- Consumer start reading from position 0 <br/>
  ![image](https://github.com/OussamaMaroufi/kafka-Debezium/assets/93825558/4e9b4bc9-5c2c-4ae3-a4f0-a90a3bec8523)
- consumer pulls messages unlicke in RabitMq consumer the broker pushes messages to consumer

- Topics goes larger
- In database if it is goes larger we perform sharding
---------
* same thing is implemented into kafka what is we call partitions
 ![image](https://github.com/OussamaMaroufi/kafka-Debezium/assets/93825558/10903f89-69fe-47cd-ae72-76e3472154a5)
- now consumer and producer are suffering they need to specify which partition and  which topic to deal with.
- 
