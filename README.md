<<<<<<< HEAD
# Simple Student REST API

A beginner-friendly Spring Boot REST API using Java 17 and Maven. It stores data in memory, so data resets when the app restarts.

## Requirements
- JDK 17 or newer
- Maven 3.6+ (or use the Maven support in your IDE)

## Run
From this folder, execute:

```bash
mvn spring-boot:run
```

The app runs at `http://localhost:8080`.

## Endpoints
- `GET /students` — list all students
- `GET /students/1` — get a student by ID
- `POST /students` — add a student
- `PUT /students/1` — update a student
- `DELETE /students/1` — delete a student

## Test POST
In Postman, select `POST`, use `http://localhost:8080/students`, choose **Body → raw → JSON**, and send:

```json
{
  "id": 3,
  "name": "Kumar",
  "course": "AWS"
}
```

## Test PUT
Use `PUT http://localhost:8080/students/1` with:

```json
{
  "name": "Arun Kumar",
  "course": "Microservices"
}
```

Note: This is a learning example, not production-ready. It does not use a database.
=======
# student-rest-api
student-rest-api
>>>>>>> 04fce692cd0f3f14ebb64844b770534f669b2c6c
