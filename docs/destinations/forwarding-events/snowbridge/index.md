---
title: "Snowbridge"
sidebar_position: 40
sidebar_label: "Snowbridge"
---

Snowbridge is a flexible, low latency tool which can replicate streams of data of any type to external destinations, optionally filtering or transforming the data along the way. It can be used to consume, transform and relay data to any third party platform which supports HTTP or is listed as a target below — in real-time.

## Features

- [Kinesis](https://aws.amazon.com/kinesis), [SQS](https://aws.amazon.com/sqs/), [PubSub](https://cloud.google.com/pubsub), [Kafka](https://kafka.apache.org/), and stdin sources

- [Kinesis](https://aws.amazon.com/kinesis), [SQS](https://aws.amazon.com/sqs/), [PubSub](https://cloud.google.com/pubsub), [Kafka](https://kafka.apache.org/), [Event Hubs](https://azure.microsoft.com/en-us/services/event-hubs/), HTTP (e.g. for an [integration with Google Tag Manager Server Side](/docs/destinations/forwarding-events/google-tag-manager-server-side/index.md)), and stdout targets

- Custom in-flight JS transformations

- Low-latency Snowplow-specific data transformations

- Statsd and Sentry reporting and monitoring interfaces

Snowbridge is a generic tool, built to work on any type of data, developed by the Snowplow team. It began life as a closed-source tool developed to deliver various requirements related to Snowplow data, and so some of the features are specific to that data.
