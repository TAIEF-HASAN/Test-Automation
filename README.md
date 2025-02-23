# Test-Automation
C# with selenium 

<h2>Topics Cover</h2>

**Introduction**
**API Basics**

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
    - 500 Internal Server Error: The server has encountered a situation it doesn't know how to handle. (GET, POST, PUT, DELETE)
    - 501 Not Implemented: The request method is not supported by the server and cannot be handled. (GET, POST, PUT, DELETE)
    - 502 Bad Gateway: The server, while acting as a gateway or proxy, received an invalid response from the upstream server. (GET, POST, PUT, DELETE)
    - 503 Service Unavailable: The server is not ready to handle the request. (GET, POST, PUT, DELETE)
    - 504 Gateway Timeout: The server, while acting as a gateway or proxy, did not get a response in time from the upstream server. (GET, POST, PUT, DELETE)
    - 505 HTTP Version Not Supported: The HTTP version used in the request is not supported by the server. (GET, POST, PUT, DELETE)5xx: Server Errors

    <h2>Postman Componets and Features</h2>
    **Postman Components and Features**

    **REQUESTS VIEW**
    **RESPONSES VIEW**
    **VARIABLES**
    **SCRIPTS**
    **COLLECTIONS**

    - **Collections**: Organize your API requests into collections for better management and sharing.
    - **Environments**: Manage different environments (e.g., development, staging, production) with environment variables.
    - **Tests**: Write tests using JavaScript to validate API responses and automate testing.
    - **Monitors**: Schedule automated tests to run at specific intervals and monitor API performance.
    - **Mock Servers**: Simulate API endpoints to test and develop without actual backend services.
    - **Documentation**: Generate and publish API documentation directly from your collections.
    - **Workspaces**: Collaborate with team members in shared workspaces.
    - **API Network**: Discover and connect with public APIs available in the Postman API Network.
    - **Integrations**: Integrate Postman with other tools and services like Jenkins, GitHub, and Slack.
    - **Postman CLI (Newman)**: Run Postman collections from the command line for CI/CD integration.
    