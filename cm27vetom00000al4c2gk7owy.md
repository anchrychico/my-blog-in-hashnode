---
title: "Activity 30:http Status Codes"
datePublished: Sun Oct 13 2024 17:39:57 GMT+0000 (Coordinated Universal Time)
cuid: cm27vetom00000al4c2gk7owy
slug: activity-30http-status-codes

---

### Understanding HTTP Status Codes in RESTful APIs

HTTP status codes are essential in RESTful APIs as they provide information about the outcome of an API request. These codes are divided into five categories, each representing a different type of response. Here’s a detailed overview of each category and the most relevant status codes within them.

---

### 1xx (Informational)

* **Purpose**: These codes indicate that the request has been received and is being processed, but there is no final response yet. These are less commonly used in typical RESTful API interactions but can be relevant in long-running requests.
    
    * **Example**:
        
        * **100 Continue**: This initial response indicating that the part of the request has been received and the client should proceed with sending the rest of the request.
            
        * **101 Switching Protocols**: Indicates that the server is switching protocols as requested by the client, e.g., from HTTP/1.1 to HTTP/2.
            

---

### 2xx (Success)

* **Purpose**: These codes indicate that the request was successfully received, understood, and processed by the server.
    
    * **200 OK**:
        
        * **Use Case**: Commonly used when a GET request successfully retrieves data.
            
        * **Example**: A GET request for user data may return:
            
            ```http
            HTTP/1.1 200 OK
            Content-Type: application/json
            {
                "id": 1,
                "name": "Alice"
            }
            ```
            
    * **201 Created**:
        
        * **Use Case**: Indicates that a POST request has successfully created a new resource.
            
        * **Example**: A POST request to create a new user may return:
            
            ```http
            HTTP/1.1 201 Created
            Content-Type: application/json
            {
                "id": 3,
                "name": "Charlie"
            }
            ```
            
    * **204 No Content**:
        
        * **Use Case**: Indicates that the request was successful, but there is no content to return, often used for DELETE operations.
            
        * **Example**: After a DELETE request for a user:
            
            ```http
            HTTP/1.1 204 No Content
            ```
            

---

### 3xx (Redirection)

* **Purpose**: These codes indicate that the client must take additional actions to complete the request. This typically involves following a redirect to a different URL.
    
    * **301 Moved Permanently**:
        
        * **Use Case**: Indicates that the resource has been permanently moved to a new URL, and the client should update its bookmarks.
            
    * **302 Found**:
        
        * **Use Case**: Indicates that the resource is temporarily located at a different URI. The client should use the original URL for future requests.
            
    * **304 Not Modified**:
        
        * **Use Case**: Used in conditional GET requests to tell the client that the resource has not changed since the last request.
            

---

### 4xx (Client Error)

* **Purpose**: These codes indicate that an error occurred due to the client's request.
    
    * **400 Bad Request**:
        
        * **Use Case**: This status is returned when the server cannot understand the request due to malformed syntax or invalid parameters.
            
        * **Example**: Missing required fields when creating a user.
            
    * **401 Unauthorized**:
        
        * **Use Case**: Authentication is required and has not been provided.
            
        * **Example**: A request for a protected resource without accompanying credentials.
            
    * **403 Forbidden**:
        
        * **Use Case**: The server understands the request, but the client does not have permission to access the resource.
            
    * **404 Not Found**:
        
        * **Use Case**: The requested resource could not be found on the server.
            
        * **Example**: Requesting a user profile with an ID that does not exist.
            

---

### 5xx (Server Error)

* **Purpose**: These codes indicate that the server failed to fulfill a valid request due to some error on its side.
    
    * **500 Internal Server Error**:
        
        * **Use Case**: Indicates that an unexpected condition was encountered and the server could not complete the request. This is a generic error message.
            
    * **503 Service Unavailable**:
        
        * **Use Case**: The server is currently unable to handle the request due to temporary overload or maintenance. The client may retry after some time.
            

---

### Conclusion

HTTP status codes are crucial for understanding the result of API requests in RESTful services. Each category of status codes provides distinct feedback about the request and helps clients react appropriately. By recognizing and implementing the correct status codes, API developers can construct APIs that communicate clearly and effectively the results of operations, enhancing user experience and interaction quality.