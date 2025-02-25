# Wikimedia Consumer Application

This is a Spring Boot application designed to consume messages from a Kafka topic.

## Table of Contents

* [Getting Started](#getting-started)
* [Prerequisites](#prerequisites)
* [Configuration](#configuration)
* [Usage](#usage)

## Getting Started

To get started with this application, follow these steps:

1. Clone the repository using `git clone https://github.com/your-username/your-repo-name.git`
2. Navigate to the project directory using `cd your-repo-name`
3. Build the project using `mvn clean package`
4. Run the application using `java -jar target/your-jar-file.jar`

## Prerequisites

* Java 8 or higher
* Apache Kafka 2.6 or higher
* Maven 3.6 or higher

## Configuration

The application configuration is located in the `application.properties` file. You can modify the configuration settings as needed.

## Usage

To use this application, simply run it and it will start consuming messages from the specified Kafka topic.

### Kafka Topic Configuration

The Kafka topic configuration is located in the `WikimediaTopicConfig.java` file. You can modify the topic settings as needed.

### Message Consumption

The application consumes messages from the Kafka topic using the `KafkaConsumer.java` class. You can modify the message consumption logic as needed.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the Apache License 2.0. See the `LICENSE` file for details.
