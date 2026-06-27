---
title: "MongoDB-backed Spring Batch jobs and more in Spring Boot 4.1"
url: "https://spring.io/blog/2026/06/21/spring-boot-41-and-spring-batch"
date: "2026-06-21"
author: "joshlong"
feed_url: "https://spring.io/blog.atom"
---
Spring Boot 4.1 now supports MongoDB as a backend for Spring Batch's JobRepository, eliminating the need for a separate SQL database. The post walks through a complete ETL example storing batch metadata in MongoDB while reading from a CSV and writing to PostgreSQL, covering tasklets and chunked processing, observability, GraalVM native image compilation, lazy datasource connection optimization, and the new spring-boot-starter-batch-data-mongodb for zero-config setup.
