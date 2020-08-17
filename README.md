### What is Apache Kafka exactly?

It is a powerful publish-subscribe messaging system that not only ensures speed, scalability, and durability but also stores and processes streams of records. Its unique design allows us to send and listen to messages in real-time.

Apache Kafka uses 5 components to process messages:

1. Topic contains records or a collection of messages.
2. Producer publishes messages to a topic or topics.
3. Consumer subscribes to topics, reads, and processes messages from the topics. It is basically a listener.
4. Broker manages the storage of messages in the topics. If there is more than one broker, it is called Cluster.
5. ZooKeeper tracks the status of cluster nodes, topics, partitions, etc. Good to know: ZooKeeper is required for running the Kafka right now, but it will be replaced with a Self-Managed Metadata Quorum in the future.

### How to run project?

1. Start ZooKeeper first
2. Start Kafka
3. Start app