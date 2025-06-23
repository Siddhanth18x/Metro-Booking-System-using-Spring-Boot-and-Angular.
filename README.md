# MetroFrontend

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.12.
Description:

The Metro Booking System is a full-stack web application designed to streamline metro travel reservations. Built using Spring Boot (Java) on the backend and Angular on the frontend, the application supports a smooth and secure user experience with features such as JWT authentication, integrated API testing via Postman, and comprehensive logging mechanisms.

Key Features:

🔐 JWT Authentication: Implements secure login and role-based access control (e.g., admin, user) using JSON Web Tokens.

📬 Postman-Ready RESTful APIs: All backend endpoints are well-structured and documented for testing with Postman, covering booking, schedules, user management, and more.

🌐 Angular Frontend: A dynamic and responsive user interface allowing users to search routes, book tickets, and manage bookings.

📄 Logging and Monitoring: Backend logs are managed using SLF4J/Logback for tracking application behavior and debugging purposes.

🗂️ Modular Design: Clean separation of concerns across backend layers (Controller, Service, Repository) and Angular modules.

📦 Spring Boot Backend: Handles business logic, database operations (likely via Spring Data JPA), and exposes secure REST APIs.

Tech Stack:

Backend: Spring Boot, Spring Security, Spring Data JPA, JWT, Maven

Frontend: Angular, TypeScript, Bootstrap/Material UI

Database: MySQL

Tools: Postman.

Use Cases:

User registration and login

Viewing available metro routes and timings

Booking and managing tickets
## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
