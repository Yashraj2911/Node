# My Node.js API

This project is a simple Node.js API built using the Express framework. It provides basic CRUD operations for managing users.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/YOUR_GITHUB_USERNAME/my-node-api.git
    cd my-node-api
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    node server.js
    ```

The server will be running on `http://localhost:3000`.

## Usage

Use an API client like Postman or `curl` to interact with the API.

## API Endpoints

### Get All Users

- **Endpoint**: `/users`
- **Method**: `GET`
- **Description**: Retrieve a list of all users.
- **Response**:
  ```json
  [
    {
      "id": 1,
      "name": "John Doe"
    },
    {
      "id": 2,
      "name": "Jane Doe"
    }
  ]

