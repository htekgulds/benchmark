# Benchmarks

## Benchmark Aspects

* Controller
* Model Binding & Validation
* Exception Handling
* Data Access (Repository and ORM)
* Dependency Injection
* Authentication & Authorization
* Performance

## Project Overview

Rest API with DB access using multiple joins

URL: GET /api/benchmark

Tables:

* Customer
    - id varchar
    - name varchar
    - password varchar
* Product Order
    - id varchar
    - created_at datetime
    - customer_id varchar
* Order Item
    - id varchar
    - name varchar
    - price bigint
    - product_id varchar
    - qty int
    - product_order_id varchar

## Projects

* .Net 6.0
* Express
* Fastify
* Nest
* Spring Boot
* Quarkus

## Inspiration

https://medium.com/@putuprema/spring-boot-vs-asp-net-core-a-showdown-1d38b89c6c2d