---
title: "Transformer Pubsub"
date: "2022-10-13"
sidebar_position: 20
---

```mdx-code-block
import {versions} from '@site/src/componentVersions';
import CodeBlock from '@theme/CodeBlock';
```

:::info

This application is available since v5.0.0.

:::

## Downloading the artifact

The asset is published as a jar file attached to the [Github release notes](https://github.com/snowplow/snowplow-rdb-loader/releases) for each version.

<span>It's also available as a Docker image on Docker Hub under <code>{`snowplow/transformer-pubsub:${versions.rdbLoader}`}</code></span>

## Configuring `snowplow-transformer-pubsub`

The transformer takes two configuration files:

- a `config.hocon` file with application settings
- an `iglu_resolver.json` file with the resolver configuration for your [Iglu](https://github.com/snowplow/iglu) schema registry.

An example of the minimal required config for the Transformer Pubsub can be found [here](https://github.com/snowplow/snowplow-rdb-loader/tree/master/config/transformer/gcp/transformer.pubsub.config.minimal.hocon) and a more detailed one [here](https://github.com/snowplow/snowplow-rdb-loader/tree/master/config/transformer/gcp/transformer.pubsub.config.reference.hocon). For details about each setting, see the [configuration reference](/docs/api-reference/loaders-storage-targets/snowplow-rdb-loader/transforming-enriched-data/stream-transformer/transformer-pubsub/configuration-reference/index.md).

See [here](/docs/api-reference/iglu/iglu-resolver/index.md) for details on how to prepare the Iglu resolver file.

:::tip

All self-describing schemas for events processed by the transformer **must** be hosted on [Iglu Server](/docs/api-reference/iglu/iglu-repositories/iglu-server/index.md) 0.6.0 or above. [Iglu Central](/docs/api-reference/iglu/iglu-repositories/iglu-central/index.md) is a registry containing Snowplow-authored schemas. If you want to use them alongside your own, you will need to add it to your resolver file. Keep it mind that it could override your own private schemas if you give it higher priority.

:::

## Running the Transformer Pubsub

The two config files need to be passed in as base64-encoded strings:

<CodeBlock language="bash">{
`$ docker run snowplow/transformer-pubsub:${versions.rdbLoader} \\
--iglu-config $RESOLVER_BASE64 \\
--config $CONFIG_BASE64
`}</CodeBlock>

```mdx-code-block
import Telemetry from "@site/docs/reusable/telemetry/_index.md"

<Telemetry name="Transformer PubSub" since="5.0.0" idSetting="telemetry.userProvidedId" disableSetting="telemetry.disable" />
```
