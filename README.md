# Backend Starter

A minimal Spring Boot REST API starter built with Java 21 and Maven.

## Requirements

- Java 21
- Maven 3.9+ (or use the Maven Wrapper if you add it)
- IntelliJ IDEA

Verify your Java installation:

```bash
java -version
```

## Build

```bash
mvn clean package
```

## Run tests

```bash
mvn test
```

## Run the application

```bash
mvn spring-boot:run
```

Then open <http://localhost:8080/api/hello>.

## Project structure

```text
src/
  main/
    java/com/example/backendstarter/
      BackendStarterApplication.java
      controller/HelloController.java
  test/
    java/com/example/backendstarter/
      BackendStarterApplicationTests.java
```

## Git setup

Initialize and commit the project:

```bash
git init
git add .
git commit -m "Initial Spring Boot skeleton"
```

Create an empty repository on GitHub, then connect and push it:

```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/backend-starter.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username. Do not commit secrets, access tokens, or local environment files.
