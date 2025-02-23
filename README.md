# Test-Automation
C# with selenium 

<h2>Catagory</h2>

**Introduction""

<h2>Groups of Status code</h2>

- 1xx: Informational
- 2xx: Success 
    - 200 OK: The request has succeeded. (GET, POST, PUT, DELETE)
    - 201 Created: The request has been fulfilled and resulted in a new resource being created. (POST, PUT)
    - 202 Accepted: The request has been accepted for processing, but the processing has not been completed. (POST, PUT)
    - 204 No Content: The server successfully processed the request, but is not returning any content. (DELETE)
- 3xx: Redirection
    - 301 Moved Permanently: The resource has been moved to a new URL permanently. (GET)
    - 302 Found: The resource is temporarily located at a different URL. (GET)
    - 304 Not Modified: The resource has not been modified since the last request. (GET)
- 4xx: Client Errors
    - 400 Bad Request: The server could not understand the request due to invalid syntax. (GET, POST, PUT, DELETE)
    - 401 Unauthorized: The client must authenticate itself to get the requested response. (GET, POST, PUT, DELETE)
    - 403 Forbidden: The client does not have access rights to the content. (GET, POST, PUT, DELETE)
    - 404 Not Found: The server can not find the requested resource. (GET, POST, PUT, DELETE)
    - 405 Method Not Allowed: The request method is known by the server but has been disabled and cannot be used. (GET, POST, PUT, DELETE)
    - 429 Too Many Requests: The user has sent too many requests in a given amount of time. (GET, POST, PUT, DELETE)
- 5xx: Server Errors