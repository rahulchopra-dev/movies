# Spring Boot Movies API

This is a simple RESTful API built with Spring Boot and MongoDB. It allows you to create, read, update, and delete movie reviews in the database. The API is designed to be easy to use and easy to extend.

## Getting Started

To get started, you will need to have the following installed on your development machine:
- Java 8 or higher
- Maven
- An IDE of your choice (such as IntelliJ IDEA or Eclipse)

Once you have the above installed, you can clone this repository and import the project into your IDE.

## Running the Application

This will start the application on port 8080. You can access the API endpoints using a tool like Postman or CURL.

## Endpoints

The following endpoints are available in the API:

- `GET /api/v1/movies`: Retrieves a list of all movies in the database.
- `GET /api/v1/movies/{id}`: Retrieves a specific movie by its ID.
- `POST /movies`: Creates a new movie in the database.
- `DELETE /movies/{id}`: Deletes an existing movie from the database.

## Built With

- [Spring Boot](https://spring.io/projects/spring-boot) - The web framework used
- [Maven](https://maven.apache.org/) - Dependency Management

## Authors

- **Rahul Chopra** - *Software Engineer*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
