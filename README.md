# Redpanda -> Microsoft Fabric integration

## Introduction
This project shows how to ingest data with Redpanda, using a self-contained Docker setup to simplify the Redpanda cluster and Redpanda connector cluster setup.
Flow:
1. Events producer sends data on Redpanda cluster on defined topic
2. Connector setup integration between Redpanda and Microsoft Fabric KQL database
3. Each new message on topic creates new entry on KQL database

## Setup


## Links
* Lab source: https://learn.microsoft.com/en-us/fabric/real-time-intelligence/get-data-kafka
* Redpanda Self-Hosted Quickstart: https://docs.redpanda.com/current/get-started/quick-start/
