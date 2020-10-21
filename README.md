# Vertx 4 Migration Guide

## Goals

- Vert.x 3 users should be guided about how to migrate their applications from Vert.x 3 to Vert.x 4
- Agile migration guide, when users will report feedback about their experience then we will update guide

## Guide structure

- [Overview](asciidoc/overview.adoc)
  - foremost users need to understand what fundamentally changes between 3 and 4
- Migration process
  - two kind of users: those migrating from latest 3 version and other still from a random version
- Components and features
  - [JSON](asciidoc/json.adoc)
  - [vertx-auth](asciidoc/auth.adoc)
  - [vertx-cassandra-client](asciidoc/cassandra.adoc)
  - [SockJS Handler](asciidoc/sockjs.adoc)
  - [Kotlin](asciidoc/kotlin.adoc)
  - [Service Proxy](asciidoc/service_proxy.adoc)
  - components rewritten in Vert.x 4
    - [vertx-jdbc-client → vertx-sql-client](asciidoc/jdbc_client.adoc)
    - [HTTP client -> HTTP client or Web client](asciidoc/http_client.adoc)
    - [vertx-redis-client](asciidoc/redis.adoc)
    - [vertx-web-api-contract -> vertx-web-openapi](asciidoc/openapi.adoc)
    - [vertx-embedded-mongo-db → vertx-wiremongo](asciidoc/wiremongo.adoc)
  - components still in Vert.x 4 but deprecated to use without an alternative in the Vert.x stack (might be elsewhere or later)
     - vertx-sync (Loom)
     - vertx-service-factory
     - vertx-http-service-factory
     - vertx-maven-service-factory
     - vertx-lang-js (es4x)
     - vertx-lang-ruby
     - ...
  - components with 4.0 breaking changes with a 3.x deprecated API
  - clustering migration process
