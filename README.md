# JPetStore Demo 6

## Overview

JPetStore Demo 6 is a sample web application that demonstrates the usage of various frameworks like MyBatis, Spring, and Tomcat. This project is designed to showcase the basic functionality of an online store with a focus on database interactions and web services.

## Technologies Used

- **Java**: Version 1.5
- **MyBatis**: Persistence framework for managing database interactions
- **Spring**: Web framework
- **Stripes**: Web framework for handling web actions
- **Tomcat**: Web server for deploying the application
- **Maven**: Build automation tool
- **HSQLDB**: In-memory relational database for testing

## Prerequisites

To run this project, you need to have the following tools installed:

- **Java JDK** (1.5 or higher)
- **Maven** (for building and managing dependencies)
- **Docker** (Optional, for containerization)

## Setup

### Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/offranking/jpetstore-6.git
cd jpetstore-6

```

 ### Build the application
 ```
 mvn clean install
 ```

### Running Locally
Using Maven + Tomcat Plugin
```
mvn tomcat7:run
```
### run
```
mvn tomcat6:run
```

Visit: http://localhost:8080/jpetstore-6

### Running with Docker
```
docker-compose up --build
```

### Stop the container
```
docker-compose down

```







