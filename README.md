# kotest-extensions-embedded-kafka

A kotest extension that spins up embedded kafka instances using the [embedded-kakfa library](https://github.com/embeddedkafka/embedded-kafka).

See [docs](https://kotest.io/docs/extensions/embedded-kafka.html).

Please create issues on the main kotest [board](https://github.com/kotest/kotest/issues).

[![Build Status](https://github.com/kotest/kotest-extensions-embedded-kafka/workflows/master/badge.svg)](https://github.com/kotest/kotest/actions)
[<img src="https://img.shields.io/maven-central/v/io.kotest.extensions/kotest-extensions-embedded-kafka.svg?label=latest%20release"/>](http://search.maven.org/#search|ga|1|kotest-extensions-embedded-kafka)
![GitHub](https://img.shields.io/github/license/kotest/kotest-extensions-embedded-kafka)
[![kotest @ kotlinlang.slack.com](https://img.shields.io/static/v1?label=kotlinlang&message=kotest&color=blue&logo=slack)](https://kotlinlang.slack.com/archives/CT0G9SD7Z)
[<img src="https://img.shields.io/nexus/s/https/oss.sonatype.org/io.kotest.extensions/kotest-extensions-embedded-kafka.svg?label=latest%20snapshot"/>](https://oss.sonatype.org/content/repositories/snapshots/io/kotest/extensions/kotest-extensions-embedded-kafka/)

### Changelog

#### 2.0.0

This change likely includes breaking changes since [embedded-kafka](https://github.com/embeddedkafka/embedded-kafka)
has gone through a major version upgrade.

* Upgrade embedded-kafka from 2.8.0 to 3.3.2
* Upgrade Kotlin from 1.4.31 to 1.6.21 (this matches kotest core as of v5.5.5)
* Continued support of jvm target 1.8
* Upgrade project gradle version from 7.5.1 to 7.6
* Remove deprecated code usage
* Switch to latest gradle build practices

#### 1.0.6

* Java 8 compatible release.

#### 1.0.5

* Upgraded to Embedded Kafka 2.8.0

#### 1.0.4

* Added overload to specify zookeeper port

#### 1.0.3

* Changed shutdown listener to wait for server shutdown.

#### 1.0.2

* Added `bootstrapServer` val to listener.

#### 1.0.1

* First release after migrating from main kotest repo to a top level project.
