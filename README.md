# Brands Service for E-commerce Application

This project is a Brands Service for an e-commerce application. The Brands Service is designed to manage product brands, enabling other microservices within the platform to interact with brand data effectively. By centralizing brand management, it ensures consistency and accuracy in the representation of brands across the e-commerce platform.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Service](#running-the-service)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Brands Service is a RESTful API built using Spring Boot. It offers endpoints for creating, updating, retrieving, and deleting product brands. This service plays a pivotal role in the product management system by ensuring that brand data is uniformly managed and easily accessible for other microservices.

## Features

- **Create Brands:** Allows the creation of new product brands with detailed descriptions.
- **Retrieve Brands:** Enables fetching of details for existing brands, supporting features like product filtering and search.

## Prerequisites

- Java 17 or higher
- Maven 3.6.3 or higher
- Spring Boot3 or higher

## Installation

1. Clone the repository:

    - ```sh
      git clone https://github.com/Agustin199811/brand-service.git
      cd category-service
      ```

2. Build the project using Maven:

    - ```sh
      mvn clean install
      ```

## Configuration

The configuration for the Category Service is located in `src/main/resources/application.propierties`. Below is an example configuration:

```properties
spring.datasource.url=jdbc:mysql://clot.cp88o8squjfi.us-east-1.rds.amazonaws.com:3306/clot
spring.datasource.username=root
spring.datasource.password=root1234

eureka.client.service-url.defaultZone=http://clot-ecommerce-ELB-1792240696.us-east-1.elb.amazonaws.com:8761/eureka/
eureka.client.register-with-eureka=true
eureka.client.fetch-registry=true
```

## Running the Service

To run the service registry, use the following command:

 ```sh
    mvn spring-boot:run
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please send us an email at
`toapantaagustin9c@gmail.com` with details about your proposed changes or improvements. We look forward to hearing from you!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
