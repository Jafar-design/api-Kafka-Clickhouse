# Project Title
This project leverages the use of Apache Kafka as a streaming service. It contains a simple producer application (producer.py) that fetches data from a forex api [Polygon.io](#https://polygon.io/docs). This then streams data into a Kafka topic where the consumer application (producer.py) feeds on the json data and inerts into a Clickhouse database.

Instructions
1. create a docker-compose file for the project