# data-engineering-kafka-stock-market-data

This project demonstrates the implementation of a data engineering pipeline for real streaming stock market data using Kafka. Key points include:

* Utilized AWS EC2 instance to host the Kafka server, establishing a connection between the EC2 instance and the local machine.
* Started ZooKeeper and Kafka servers on the local machine to facilitate data streaming.
* Developed a Python script in Jupyter Notebook to simulate real streaming data by sending historical stock market data from a Kafka producer to a Kafka consumer.
* Leveraged the consumer side of Kafka to load the simulated streaming data into an S3 bucket, enabling storage and further analysis.

Here is the architecture design implemented:
![Stock-market-data-kafka drawio (1)](https://github.com/hiteshmadapathi/data-engineering-kafka-stock-market-data/assets/54840773/193dbb9f-8d2e-44bc-847f-4699cb5574d7)

By building this pipeline, the project showcases the integration of Kafka, AWS EC2, and S3 to process and store real streaming stock market data.
