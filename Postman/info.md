# Postman API Workshop Documentation

## Overview
This document provides a concise guide for setting up and working with Postman for API testing. The content is based on a workshop focused on understanding APIs, Postman, and basic API testing methods.

---

## Table of Contents
1. [Introduction to APIs](#introduction-to-apis)
2. [Postman Overview](#postman-overview)
3. [JSON Data Format](#json-data-format)
4. [Hands-On Practice with Postman](#hands-on-practice)
5. [API Status Codes](#api-status-codes)
6. [Recap and Further Resources](#recap-and-resources)

---

## <a name="introduction-to-apis"></a> 1. Introduction to APIs
- **Definition**: APIs act as intermediaries enabling communication between systems.
- **Analogy**: APIs are like a waiter delivering orders (data) between a client (table) and server (kitchen).

---

## <a name="postman-overview"></a> 2. Postman Overview
- **Features**:
  - Simplifies API testing.
  - Allows GET/POST requests.
  - Analyzes response data and status codes.
  - Supports task automation for repetitive testing.

---

## <a name="json-data-format"></a> 3. JSON Data Format
- **Key Characteristics**:
  - Lightweight and efficient for data exchange.
  - Universal compatibility across programming languages.
  - Human-readable structure.

---

## <a name="hands-on-practice"></a> 4. Hands-On Practice with Postman
### GET Requests
- **Objective**: Retrieve data from an API.
- **Steps**:
  1. Use `GET` to fetch data from API endpoints (e.g., `/posts`, `/users`).
  2. Analyze the returned JSON structure and `200 OK` status code.

### POST Requests
- **Objective**: Send data to an API.
- **Steps**:
  1. Use `POST` to submit JSON data to an endpoint.
  2. Include a JSON object in the request body.
  3. Confirm success with the `201 Created` status code and review the updated resource.

### Sample API Endpoints for Practice:
- `https://jsonplaceholder.typicode.com/posts` (GET, POST)
- `https://jsonplaceholder.typicode.com/comments`
- `https://jsonplaceholder.typicode.com/users`

---

## <a name="api-status-codes"></a> 5. API Status Codes

### Informational Responses (100–199)
- **100 Continue**: Indicates that the initial part of the request was received, and the client should continue sending the request.
- **101 Switching Protocols**: The server is switching protocols as requested by the client.

### Successful Responses (200–299)
- **200 OK**: The request was successful, and the response contains the requested data.
- **201 Created**: A new resource was created successfully as a result of the request.
- **202 Accepted**: The request has been accepted for processing but is not yet completed.
- **204 No Content**: The request was successful, but there is no content to return.

### Redirection Messages (300–399)
- **301 Moved Permanently**: The requested resource has been permanently moved to a new URL.
- **302 Found**: The resource is temporarily available at a different URL.
- **304 Not Modified**: The resource has not changed since the last request.

### Client Error Responses (400–499)
- **400 Bad Request**: The server could not process the request due to invalid syntax or data.
- **401 Unauthorized**: Authentication is required and has either failed or not been provided.
- **403 Forbidden**: The server understood the request but refuses to authorize it.
- **404 Not Found**: The server cannot find the requested resource.

### Server Error Responses (500–599)
- **500 Internal Server Error**: The server encountered an unexpected condition that prevented it from fulfilling the request.
- **502 Bad Gateway**: The server received an invalid response from an upstream server.
- **503 Service Unavailable**: The server is currently unavailable due to maintenance or overload.
- **504 Gateway Timeout**: The server did not receive a timely response from an upstream server.

---

## <a name="recap-and-resources"></a> 6. Recap and Further Resources
### Recap
- APIs facilitate communication between systems.
- Postman simplifies API testing and debugging.
- JSON is the standard data format for API interactions.
- Practice with GET and POST methods to understand API workflows.

### Resources
- [JSON Placeholder Documentation](https://jsonplaceholder.typicode.com)
- [Postman Learning Center](https://learning.postman.com)
- [HTTP Status Code Guide](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)

---

**Thank You!**  
Continue exploring APIs by practicing with Postman and building projects.
