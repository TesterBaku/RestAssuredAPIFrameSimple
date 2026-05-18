# RestAssuredAPIFrameSimple

A simple, readable **API test automation framework** built with **Java + RestAssured + Maven + TestNG**. Designed so a new tester can clone it and write their first test in minutes.

## What's inside

- Layered structure: request specs, endpoints, models, and tests
- TestNG runner with XML suite configuration
- Data-driven tests via TestNG `@DataProvider`
- Reusable request and response specifications
- Maven build with dependency management

## Stack

`Java` · `RestAssured` · `Maven` · `TestNG`

## Getting started

```bash
mvn clean test
```

Run a single suite:

```bash
mvn test -DsuiteXmlFile=testng.xml
```

## Why this repo

REST API testing without the boilerplate of larger enterprise frameworks. Good baseline when you want something working today.
