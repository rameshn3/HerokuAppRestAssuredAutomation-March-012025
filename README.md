# HerokuApp Rest-Assured TestNG API Testing Automation

This project demonstrates API testing automation using Rest-Assured and TestNG. It focuses on testing the endpoints of the HerokuApp service, providing examples of how to structure and execute automated API tests.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Project Setup](#project-setup)
- [Running the Tests](#running-the-tests)
- [Project Structure](#project-structure)
- [Reporting](#reporting)
- [References](#references)

## Introduction

The goal of this project is to showcase how to use Rest-Assured in conjunction with TestNG to perform automated testing of RESTful APIs. Rest-Assured simplifies the process of interacting with APIs, while TestNG provides a robust framework for organizing and running tests.

## Features

- **HTTP Methods Coverage**: Includes tests for GET, POST, PUT, PATCH, and DELETE requests.
- **Assertions**: Utilizes Hamcrest Matchers for validating API responses.
- **Logging**: Implements Log4j for capturing logs during test execution.
- **Data Handling**: Uses Lombok to generate getters and setters for request payloads.
- **TestNG Integration**: Leverages TestNG's features for test execution and reporting.

## Prerequisites

Before setting up the project, ensure you have the following installed:

- [Java Development Kit (JDK) 8 or higher](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html)
- [Apache Maven](https://maven.apache.org/install.html)
- [An IDE or text editor of your choice](https://www.jetbrains.com/idea/download/)

## Project Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/rameshn3/HerokuAppRestAssuredAutomation-March-012025.git
   cd HerokuAppRestAssuredAutomation-March-012025
   
  ** Install Dependencies:**

Ensure all Maven dependencies are downloaded by running:
mvn clean install
Running the Tests

To execute the tests, use the following Maven command:
mvn test


