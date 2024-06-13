# REST API with Spring Boot and Angular


CRUD Angular + Spring demonstrating Has-Many relationship.

This API is to showcase, especially for beginners, what a basic CRUD API that's close to being Production-ready looks like.

It was developed in the [CRUD Angular + Spring Course](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBpwaVgAPxTxhdX_TfSVlTcY) by Loiane Groner (Instructor):
- [Instagram](https://www.instagram.com/loiane/)
- [Youtube](https://www.youtube.com/@loianegroner)
- [Github](https://github.com/loiane)


## 💻 Tecnologies

- Java 21
- Spring Boot 3 (Spring 6)
- Maven
- JPA + Hibernate
- MySQL
- Angular v18
- Angular Material

## ⌨️ Editor / IDE

- Visual Studio Code
- Java Extensions [link](https://marketplace.visualstudio.com/items?itemName=loiane.java-spring-extension-pack)
- Angular Extensions [link](https://marketplace.visualstudio.com/items?itemName=loiane.angular-extension-pack)

## Some functionalities available in the API

- ✅ Java model class with validation
- ✅ JPA repository
- ✅ JPA Pagination
- ✅ MySQL database (you can use any database of your preference)
- ✅ Controller, Service, and Repository layers
- ✅ Has-Many relationships (Course-Lessons)
- ✅ Java 17 Records as DTO (Data Transfer Object)
- ✅ Hibernate / Jakarta Validation
- ✅ Spring Docs - Swagger (https://springdoc.org/v2/)


### Not implemented (maybe in a future version)

- Security (Authorization and Authentication)
- Caching
- Data Compression
- Throttling e Rate-limiting
- Profiling the app
- Test Containers
- Docker Build
- JUnit 5 + Mockito (back-end tests)
- Karma + Jasmine (front-end tests)
- Unit tests for all layers (repository, service, controller)
- Unit and Integration tests for components, services, pipes, guards
- Test coverage for tests


## Some functionalities available in the front end

- ✅ Angular Standalone components (Angular v16+)
- ✅ Angular Material components
- ✅ List of all courses with pagination
- ✅ Form to update/create courses with lessons (has-many - FormArray)
- ✅ View only screen
- ✅ TypedForms (Angular v14+)
- ✅ Presentational x Smart Components


## Screenshots

Main Page with Pagination

<p align="center">
  <img src="./docs/main.jpeg" alt="Main Page" width="100%">
</p>

Form with One to Many (Course-Lessons)

<p align="center">
  <img src="./docs/form.jpeg" alt="Form Page" width="100%">
</p>

View Page of the YouTube Player Instructor

<p align="center">
  <img src="./docs/view.jpeg" alt="View Page" width="100%">
</p>

## ❗️Executing the code locally

### Executing the back-end

You need to have Java and Maven installed and configured locally.

Open the `crud-spring` project in your favorite IDE as a Maven project and execute it as Spring Boot application.

### Executing the front-end

You need to have Node.js / NPM installed locally.

1. Install all the required dependencies:

```
npm install
```

2. Execute the project:

```
npm run start
```

This command will run the Angular project with a proxy to the Java server, without requiring CORS.

Open your browser and access **http://localhost:4200** (Angular default port).

#### Upgrading Angular

```
ng update
```

Then

```
ng update @angular/cli @angular/core @angular/cdk @angular/material @angular/youtube-player --force
```
