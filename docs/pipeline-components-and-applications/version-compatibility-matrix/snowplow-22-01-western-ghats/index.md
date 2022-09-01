---
title: "Snowplow 22.01 Western Ghats"
date: "2022-01-31"
sidebar_position: 99970
---

### Recommended Stack

Please note, the `x` indicates that we recommend always being on the latest patched version. Components which have been updated since the last release are **highlighted**.

#### AWS

<table class="has-fixed-layout"><tbody><tr><td class="has-text-align-center" data-align="center"><mark  class="has-inline-color has-vivid-purple-color"><strong>Stream Collector</strong></mark></td><td class="has-text-align-center" data-align="center"><mark  class="has-inline-color has-vivid-purple-color"><strong>Stream Enrich</strong></mark></td><td class="has-text-align-center" data-align="center"><mark  class="has-inline-color has-vivid-purple-color"><strong>Dataflow Runner</strong></mark></td><td class="has-text-align-center" data-align="center">Sqs2Kinesis</td></tr><tr><td class="has-text-align-center" data-align="center"><a href="http://github.com/snowplow/stream-collector/releases">v2.4.5</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/stream-enrich/releases">v2.0.5</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/dataflow-runner/releases">v0.6.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow-incubator/sqs2kinesis/releases/tag/1.0.0" target="_blank" rel="noreferrer noopener">v1.0.x</a></td></tr></tbody></table>

<table class="has-fixed-layout"><tbody><tr><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">S3 Loader</mark></strong></td><td class="has-text-align-center" data-align="center"><strong><span class="has-inline-color has-vivid-purple-color">RDB Loader</span></strong></td><td class="has-text-align-center" data-align="center"><strong><span class="has-inline-color has-vivid-purple-color">Snowflake Loader</span></strong></td><td class="has-text-align-center" data-align="center">Elasticsearch<br/>Loader</td></tr><tr><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-s3-loader/releases">v2.1.3</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-rdb-loader/releases">v2.1.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow-incubator/snowplow-snowflake-loader/releases">v0.9.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-elasticsearch-loader/releases">v1.0.5</a></td></tr></tbody></table>

#### GCP

<table class="has-fixed-layout"><tbody><tr><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">Stream Collector</mark></strong></td><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">Beam Enrich</mark></strong></td><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">Enrich PubSub</mark></strong></td><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">GCS Loader</mark></strong></td><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">BigQuery Stream Loader</mark></strong></td></tr><tr><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/stream-collector/releases">v2.4.5</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/enrich/releases">v2.0.5</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/enrich/releases">v2.0.5</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow-incubator/snowplow-google-cloud-storage-loader/releases">v0.3.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow-incubator/snowplow-bigquery-loader/releases">v1.1.x</a></td></tr></tbody></table>

#### Iglu

<table class="has-fixed-layout"><tbody><tr><td class="has-text-align-center" data-align="center">Iglu Server</td><td class="has-text-align-center" data-align="center">igluctl</td><td class="has-text-align-center" data-align="center"><strong><span class="has-inline-color has-vivid-purple-color">Iglu Central</span></strong></td></tr><tr><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow-incubator/iglu-server/releases">v0.7.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow-incubator/igluctl/releases/">v0.8.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/iglu-central/releases" target="_blank" rel="noreferrer noopener">R132</a></td></tr></tbody></table>

#### Trackers

<table class="has-fixed-layout"><tbody><tr><td class="has-text-align-center" data-align="center"><strong><span class="has-inline-color has-vivid-purple-color">JS (Web &amp; Node)</span></strong></td><td class="has-text-align-center" data-align="center"><strong><span class="has-inline-color has-vivid-purple-color">Android</span></strong></td><td class="has-text-align-center" data-align="center"><span class="has-inline-color has-vivid-purple-color"><strong>iOS</strong></span></td><td class="has-text-align-center" data-align="center">React Native</td><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">Flutter</mark></strong></td><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">Java</mark></strong></td><td class="has-text-align-center" data-align="center">.NET</td><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">Python</mark></strong></td></tr><tr><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-javascript-tracker/releases">v3.3.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-android-tracker/releases">v3.0.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-objc-tracker/releases">v3.0.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-react-native-tracker/releases">v1.0.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow-incubator/snowplow-flutter-tracker/releases">v0.1.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-java-tracker/releases">v0.11.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-dotnet-tracker/releases">v1.1.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-python-tracker/releases">v0.10.x</a></td></tr></tbody></table>

<table class="has-fixed-layout"><tbody><tr><td class="has-text-align-center" data-align="center">AMP</td><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">Roku</mark></strong></td><td class="has-text-align-center" data-align="center">Unity</td><td class="has-text-align-center" data-align="center">PHP</td><td class="has-text-align-center" data-align="center">Golang</td><td class="has-text-align-center" data-align="center">Scala</td><td class="has-text-align-center" data-align="center"><strong><mark  class="has-inline-color has-vivid-purple-color">Ruby</mark></strong></td><td class="has-text-align-center" data-align="center">C++</td></tr><tr><td class="has-text-align-center" data-align="center"><a href="/docs/collecting-data/collecting-from-own-applications/google-amp-tracker/">v1.0.3</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow-incubator/snowplow-roku-tracker/releases">v0.2.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-unity-tracker/releases">v0.5.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-php-tracker/releases">v0.4.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-golang-tracker/releases">v2.4.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-scala-tracker/releases">v1.0.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-ruby-tracker/releases">v0.8.x</a></td><td class="has-text-align-center" data-align="center"><a href="https://github.com/snowplow/snowplow-cpp-tracker/releases">v0.1.x</a></td></tr></tbody></table>

#### Data Modeling

##### SQL Runner

<table class="has-fixed-layout"><tbody><tr><td>Redshift web model</td><td>BigQuery web model</td><td>Snowflake web model</td></tr><tr><td><a href="https://github.com/snowplow/data-models/releases">v1.2.x</a></td><td><a href="https://github.com/snowplow/data-models/releases">v1.0.x</a></td><td><a href="https://github.com/snowplow/data-models/releases">v1.0.x</a></td></tr></tbody></table>

<table class="has-fixed-layout"><tbody><tr><td>Redshift mobile model</td><td>BigQuery mobile model</td><td>Snowflake mobile model</td></tr><tr><td><a href="https://github.com/snowplow/data-models/releases">v1.1.x</a></td><td><a href="https://github.com/snowplow/data-models/releases">v1.1.x</a></td><td><a href="https://github.com/snowplow/data-models/releases">v1.1.x</a></td></tr></tbody></table>

<table class="has-fixed-layout"><tbody><tr><td>SQL Runner</td></tr><tr><td><a href="https://github.com/snowplow/sql-runner/releases">v0.9.x</a></td></tr></tbody></table>

##### dbt

<table class="has-fixed-layout"><tbody><tr><td><strong><span class="has-inline-color has-vivid-purple-color">dbt-snowplow-web</span></strong></td><td><strong><span class="has-inline-color has-vivid-purple-color">dbt-snowplow-utils</span></strong></td><td><strong><span class="has-inline-color has-vivid-purple-color">dbt</span></strong></td></tr><tr><td><a href="https://github.com/snowplow/dbt-snowplow-web/releases" target="_blank" rel="noreferrer noopener">v0.5.x</a></td><td><a href="https://github.com/snowplow/dbt-snowplow-utils/releases" target="_blank" rel="noreferrer noopener">v0.5.x</a></td><td><a href="https://github.com/dbt-labs/dbt/releases">v1.0.x</a></td></tr></tbody></table>

#### Testing

<table class="has-fixed-layout"><tbody><tr><td><strong><mark  class="has-inline-color has-vivid-purple-color">Mini</mark></strong></td><td>Micro</td></tr><tr><td><a href="https://github.com/snowplow/snowplow-mini/releases">v0.13.x</a></td><td><a href="https://github.com/snowplow-incubator/snowplow-micro/releases">v1.2.x</a></td></tr></tbody></table>

#### Analytics SDKs

<table class="has-fixed-layout"><tbody><tr><td>Scala</td><td>JavaScript</td><td>Python</td><td>.NET</td><td>Golang</td></tr><tr><td><a href="https://github.com/snowplow/snowplow-python-analytics-sdk/releases">v2.1.x</a></td><td><a href="https://github.com/snowplow-incubator/snowplow-js-analytics-sdk/releases">v0.3.0</a></td><td><a href="https://github.com/snowplow/snowplow-python-analytics-sdk/releases">v0.2.x</a></td><td><a href="https://github.com/snowplow/snowplow-dotnet-analytics-sdk/releases">v0.2.x</a></td><td><a href="https://github.com/snowplow/snowplow-golang-analytics-sdk/releases" target="_blank" rel="noreferrer noopener">v0.1.x</a></td></tr></tbody></table>

We hope that the above provides clarity on our recommended stack, however if you have any questions or feedback please reach out to us on [discourse](https://discourse.snowplow.io/).