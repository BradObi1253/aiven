# Aiven Kafka Sample Code
Aiven Kafka manages distributed data streaming which is deployed in the cloud. Kafka stores a large number of records. Each contains a small amount of data, usually for a limited and storaged and organised into topics and partitions so that data streams can be handled at once. Kafka would require a producer and a consumer.

Producer is responsible for generating the events or data in a user session in sequence while running multiple threads to simulate multiple users hitting the site. The generated data would be sent over and ingest by the kafka consumer.

Consumer is responsible for receiving and data sent over from the producer. Kafka consumer would be able to process data published by producers

Using the Aiven console workflow as reference , I designed a sample code to demonstrate a data pipeline. The goal is to demonstrate how Aiven Kafka ingest clickstream data and push the data into an opensearch. Opensearch will be acting as the consumer.
