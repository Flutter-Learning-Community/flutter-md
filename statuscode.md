# Status Code


* ## 1xx – informational
* ## 2xx – successful
* ## 3xx – redirection
* ## 4xx – client error
* ## 5xx – server error
---


+ ## 100 - Continue
    * Indicates that everything so far is OK and that the client should continue with the request or ignore it if it is already finished.
+ ## 102 - Processing
    * To inform the client that the server has accepted the complete request, but has not yet completed it.
+ ## 200 - Successful request.

+ ## 201 - For a successful request and data was created.

+ ## 204 - For empty response.
    * Indicates that a request has succeeded, but that the client doesn't need to navigate away from its current page.
+ ## 400 - This is used for Bad Request. 
    * If you enter something wrong or you missed some required parameters, then the request would not be understood by the server.
+ ## 401 -This is used for Unauthorized Access.
    * If the request authentication failed or the user does not have permissions for the requested operations.

+ ## 403 - This is for Forbidden or Access Denied.
    * The server understands the request but refuses to authorize it.

+ ## 404 - The Data Not Found.
    * If the server does not know, or has no facility to determine, whether or not the condition is permanent.
+ ## 405 - Method not allowed or if the requested method is not supported.
    * The server knows the request method, but the target resource doesn't support this method.
+ ## 417 - validation error
    * Indicates that the expectation given in the request's Expect header could not be met.

+ ## 500 - Internal Server Error.
    * The server encountered an unexpected condition that prevented it from fulfilling the request.
+ ## 502 - Bad Gateway
    * The server, while acting as a gateway or proxy, received an invalid response from the upstream server.
+ ## 503 - Service Unavailable
    * The server is not ready to handle the request.



