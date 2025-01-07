# Spring Boot Demo Project

This project is a Spring Boot application designed to manage students and subjects. It provides RESTful APIs to perform CRUD operations on students and subjects.

## Features

- Create and retrieve students
- Create and retrieve subjects
- RESTful APIs for easy integration

## Prerequisites

- Java Development Kit (JDK) 19 or higher
- Maven 3.6.0 or higher
- Postman for testing APIs (optional)

## Setup Instructions

1. Clone the repository

   ```bash
   git clone <repository-url>
   cd spring-boot-demo-project
   ```

2. Build the project

   ```bash
   mvn clean install
   ```

3. Run the application

   ```bash
   mvn spring-boot:run
   ```

   The application will start and be accessible at `http://localhost:8080`.

## API Endpoints

The following API endpoints are available:

### Students

- Create Student

  - URL: `POST http://localhost:8080/api/students`
  - Headers: `Content-Type: application/json`
  - Body:
    ```json
    {
      "name": "Rachita",
      "address": "Kolhapur"
    }
    ```

- Get All Students

  - URL: `GET http://localhost:8080/api/students`

### Subjects

- Create Subject

  - URL: `POST http://localhost:8080/api/subjects`
  - Headers: `Content-Type: application/json`
  - Body:
    ```json
    {
      "name": "Mathematics"
    }
    ```

- Get All Subjects

  - URL: `GET http://localhost:8080/api/subjects`

## Testing with Postman

1. Import the provided Postman collection file `SpringBootDemoProject_Updated.postman_collection.json` into Postman.
2. Use the collection to test the API endpoints as described above.

## License

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

## Acknowledgments

- Spring Boot documentation: [https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot)
- Postman: [https://www.postman.com/](https://www.postman.com/)



