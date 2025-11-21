# API Documentation

## REST API Endpoints

### 1. Get Users
- **Endpoint**: `/api/users`
- **Method**: `GET`
- **Description**: Retrieves a list of users.
- **Response**:
  ```json
  [
    {"id": 1, "name": "John Doe"},
    {"id": 2, "name": "Jane Doe"}
  ]
  ```

### 2. Get User by ID
- **Endpoint**: `/api/users/{id}`
- **Method**: `GET`
- **Description**: Retrieves a user by their ID.
- **Response**:
  ```json
  {"id": 1, "name": "John Doe"}
  ```

### 3. Create User
- **Endpoint**: `/api/users`
- **Method**: `POST`
- **Description**: Creates a new user.
- **Request**:
  ```json
  {"name": "New User"}
  ```
- **Response**:
  ```json
  {"id": 3, "name": "New User"}
  ```

## WebSocket Events

### 1. User Connected
- **Event**: `user_connected`
- **Description**: Fired when a user connects to the WebSocket.

### 2. Message Received
- **Event**: `message_received`
- **Description**: Fired when a message is received.

## Authentication
- **Method**: `Bearer Token`
- **Description**: Users must provide a valid token in the `Authorization` header.

## Error Handling
- **Common Errors**:
  - `401 Unauthorized`: Token is missing or invalid.
  - `404 Not Found`: The requested resource does not exist.
  - `500 Internal Server Error`: An unexpected error occurred.

## Example Requests

### 1. Get Users Example Request
```bash
curl -X GET \
  http://yourapi.com/api/users \
  -H 'Authorization: Bearer <your_token>'
```

### 2. Create User Example Request
```bash
curl -X POST \
  http://yourapi.com/api/users \
  -H 'Authorization: Bearer <your_token>' \
  -H 'Content-Type: application/json' \
  -d '{"name": "New User"}'
```
