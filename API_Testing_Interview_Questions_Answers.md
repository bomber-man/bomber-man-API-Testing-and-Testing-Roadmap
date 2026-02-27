# API Testing Interview Questions and Answers

## 1. What is an API?

An API (Application Programming Interface) is a set of rules and
protocols that allows different software applications to communicate
with each other. It defines how requests and responses should be
structured.

------------------------------------------------------------------------

## 2. What is API Testing?

API Testing is a type of software testing that validates APIs directly.
It focuses on business logic, data validation, security, and performance
rather than the user interface.

------------------------------------------------------------------------

## 3. Difference between API Testing and UI Testing

  API Testing           UI Testing
  --------------------- ----------------------------
  Tests backend logic   Tests frontend interface
  Faster execution      Slower execution
  More stable           UI changes may break tests
  No UI dependency      UI dependent

------------------------------------------------------------------------

## 4. What are the types of APIs?

-   REST
-   SOAP
-   GraphQL
-   gRPC

------------------------------------------------------------------------

## 5. What is REST?

REST (Representational State Transfer) is an architectural style that
uses HTTP methods to perform operations on resources. It is stateless
and commonly uses JSON format for data exchange.

------------------------------------------------------------------------

## 6. What is SOAP?

SOAP (Simple Object Access Protocol) is a protocol that uses XML
messages and works over HTTP, SMTP, and other protocols. It is strict
and supports built-in security standards.

------------------------------------------------------------------------

## 7. What are HTTP Methods?

-   GET -- Retrieve data
-   POST -- Create new resource
-   PUT -- Update entire resource
-   PATCH -- Partial update
-   DELETE -- Remove resource

------------------------------------------------------------------------

## 8. Difference between PUT and PATCH?

PUT updates the entire resource, while PATCH updates only specific
fields of a resource.

------------------------------------------------------------------------

## 9. What are HTTP Status Codes?

-   200 -- OK
-   201 -- Created
-   400 -- Bad Request
-   401 -- Unauthorized
-   403 -- Forbidden
-   404 -- Not Found
-   500 -- Internal Server Error

------------------------------------------------------------------------

## 10. Difference between 401 and 403?

401 indicates authentication failure, while 403 indicates authorization
failure (no permission).

------------------------------------------------------------------------

## 11. What tools are used for API Testing?

Common tools include: - Postman - Rest Assured - SoapUI - JMeter

------------------------------------------------------------------------

## 12. What is JSON and XML?

JSON is a lightweight data-interchange format. XML is a markup language
used to store and transport data.

------------------------------------------------------------------------

## 13. Difference between JSON and XML?

  JSON             XML
  ---------------- ----------------
  Lightweight      Heavier
  Faster parsing   Slower parsing
  Easier to read   More complex

------------------------------------------------------------------------

## 14. What is an Endpoint?

An endpoint is a specific URL where an API can be accessed.

------------------------------------------------------------------------

## 15. What is Base URI and Base Path?

Base URI is the root address of the API, while Base Path is the specific
resource path.

------------------------------------------------------------------------

## 16. What is Authentication in APIs?

Authentication verifies the identity of a user or system before granting
access.

------------------------------------------------------------------------

## 17. Types of Authentication used in APIs

-   Basic Authentication
-   Bearer Token
-   OAuth 2.0
-   API Key

------------------------------------------------------------------------

## 18. What is OAuth 2.0?

OAuth 2.0 is an authorization framework that enables applications to
obtain limited access to user accounts using tokens.

------------------------------------------------------------------------

## 19. What is a Bearer Token?

A Bearer Token is an access token passed in the Authorization header to
authenticate API requests.

------------------------------------------------------------------------

## 20. What validations are performed in API Testing?

-   Status code validation
-   Response body validation
-   Header validation
-   Schema validation
-   Response time validation
-   Database validation

------------------------------------------------------------------------

## 21. How do you perform API Automation?

By using tools like Rest Assured or Postman, writing scripts, adding
assertions, handling dynamic data, and integrating into CI/CD pipelines.

------------------------------------------------------------------------

## 22. How do you validate Response Schema?

Using JSON schema validation to ensure the response structure matches
the expected format.

------------------------------------------------------------------------

## 23. What is Contract Testing?

Contract Testing ensures that API consumers and providers follow a
predefined request and response structure agreement.

------------------------------------------------------------------------

## 24. Difference between API Testing and Unit Testing?

  API Testing             Unit Testing
  ----------------------- -----------------------------
  Tests complete API      Tests small code units
  Validates integration   Validates individual method

------------------------------------------------------------------------

## 25. How do you test Error Handling in APIs?

By sending invalid inputs, missing fields, wrong HTTP methods, and
invalid authentication tokens.

------------------------------------------------------------------------

## 26. How do you handle Dynamic Values in API Testing?

Store response values in variables and reuse them in subsequent
requests.

------------------------------------------------------------------------

## 27. What is Mocking in API Testing?

Mocking simulates API responses when the actual service is unavailable.

------------------------------------------------------------------------

## 28. How do you perform Load Testing on APIs?

Using performance testing tools to simulate multiple users and measure
response time, throughput, and error rate.

------------------------------------------------------------------------

## 29. What are common challenges in API Testing?

-   Authentication handling
-   Dynamic tokens
-   Data dependency
-   Environment setup
-   Versioning issues

------------------------------------------------------------------------

## 30. How do you integrate API Tests into CI/CD?

Store test scripts in version control, configure CI tools to execute
tests automatically on build, generate reports, and fail builds on test
failure.

------------------------------------------------------------------------

**End of Document**
