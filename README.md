# Building-Full-CRUD-RESTful-APIs
# Event Management API

A simple Flask-based RESTful API for managing events.

## Endpoints

### 1. List All Events
* **URL:** `/events`
* **Method:** `GET`
* **Response:** `200 OK` with a list of event objects.

### 2. Create an Event
* **URL:** `/events`
* **Method:** `POST`
* **Data:** `{"title": "Event Name"}`
* **Response:** `201 Created` with the new event object.

### 3. Update an Event Title
* **URL:** `/events/<id>`
* **Method:** `PATCH`
* **Data:** `{"title": "Updated Name"}`
* **Response:** `200 OK` or `404 Not Found`.

### 4. Delete an Event
* **URL:** `/events/<id>`
* **Method:** `DELETE`
* **Response:** `200 OK` or `404 Not Found`.