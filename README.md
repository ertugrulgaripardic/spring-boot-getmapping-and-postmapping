# Spring Boot GET and POST Mapping Demo

## Overview
This project demonstrates the use of `@GetMapping` and `@PostMapping` annotations in a Spring Boot application. It includes simple implementations for handling HTTP GET and POST requests to showcase how data can be retrieved and submitted to a server using these methods.

## Features
- Handle GET requests to fetch data from the server.
- Handle POST requests to send data to the server.
- A simple Thymeleaf integration for rendering views.
- Basic unit tests to ensure the functionality of the controllers.

## Technologies Used
- Spring Boot
- Thymeleaf
- Java 11+
- Maven

## Running the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/ertugrulgaripardic/spring-boot-getmapping-and-postmapping.git
    ```
2. Navigate to the project directory and build the project:
    ```bash
    cd spring-boot-getmapping-and-postmapping
    mvn clean install
    ```
3. Run the application:
    ```bash
    mvn spring-boot:run
    ```
4. Access the application in your browser at `http://localhost:8080`.

## Usage
- **GET Request**: Navigate to `/get` to see a simple data retrieval example.
- **POST Request**: Use `/post` to submit data through an HTML form (Thymeleaf).

## Contributing
Feel free to submit issues or pull requests if you want to contribute to the project.
## License
This project is licensed under the MIT License.
