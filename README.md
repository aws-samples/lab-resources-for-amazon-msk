# Amazon MSK Labs resources
This repository contains assets to be used in the [Amazon MSK Labs](https://amazonmsk-labs.workshop.aws/en/overview/overview.html). The `setup.sh` script is meant to configure (via user data) an Amazon EC2 client instance. It automates several steps (most of which are described in the [Getting Started Using Amazon MSK](https://docs.aws.amazon.com/msk/latest/developerguide/getting-started.html) documentation page), such as:
- Installing Java, Python, and the AWS Command Line Interface (CLI)
- Downloading the Apache Kafka client libraries and tools
- Building the sample clickstream producer (available at https://github.com/aws-samples/clickstream-producer-for-apache-kafka)
- Setting up a local Confluent Schema Registry
