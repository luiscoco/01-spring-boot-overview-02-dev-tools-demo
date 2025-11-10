# My Cool App

This is a simple Spring Boot application that demonstrates the use of Spring Boot's web and devtools starters.

## Features

*   Exposes a REST endpoint at `/` that returns "Hello World!".
*   Exposes a REST endpoint at `/workout` that returns "Run a hard 5k!".
*   Exposes a REST endpoint at `/fortune` that returns "Today is your lucky day.".

## Dependencies

*   **Spring Boot Starter Web:** This starter is essential for building web applications, including RESTful applications like this one, using Spring MVC. It provides all the necessary dependencies, including an embedded Apache Tomcat server, so you can run your application without needing to deploy it to an external web server.

*   **Spring Boot DevTools:** This dependency provides a set of tools to make the development process more efficient. Its key features include:
    *   **Automatic Restart:** When you make changes to your code, DevTools automatically restarts the application, so you can see your changes reflected quickly without a manual restart.
    *   **LiveReload:** DevTools includes an embedded LiveReload server that can automatically trigger a browser refresh when resources are changed.

## How to Run

1.  Clone the repository.
2.  Navigate to the project directory.
3.  Run the application using the Maven wrapper: `./mvnw spring-boot:run`
4.  The application will be available at `http://localhost:8080`.