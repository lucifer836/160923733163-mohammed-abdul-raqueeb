# Task App

## Description
This is a Spring Boot application to manage tasks.  
It supports creating, reading, updating, and deleting tasks (CRUD operations).

---

## How to Run

1. Make sure you have **Java** and **Maven** installed.  
2. Open a terminal/command prompt in the project folder.  
3. Run the application using Maven:  
```bash
mvn spring-boot:run
```

Open your browser and go to:
`http://localhost:8080`

## API Endpoints

| Operation      | URL         | Method |
| -------------- | ----------- | ------ |
| Get all tasks  | /tasks      | GET    |
| Get task by ID | /tasks/{id} | GET    |
| Add task       | /tasks      | POST   |
| Update task    | /tasks/{id} | PUT    |
| Delete task    | /tasks/{id} | DELETE |


## JSON for POST Request
```json
{
  "id": 1,
  "title": "Test Task",
  "description": "This is a test task",
  "status": "TODO"
}
```

## Images for Operations

Place these images in src/main/resources/static/images/:

| Operation | File Name  |
| --------- | ---------- |
| GET       | get.png    |
| POST      | post.png   |
| PUT       | put.png    |
| DELETE    | delete.png |

<img src="/images/get.png" alt="Get Operation">
<img src="/images/post.png" alt="Post Operation">
<img src="/images/put.png" alt="Put Operation">
<img src="/images/delete.png" alt="Delete Operation">

