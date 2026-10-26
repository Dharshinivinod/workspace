# API Testing and Automation Using Postman

## Project Overview

This project focuses on testing REST APIs using Postman, JavaScript-based assertions, environment variables, request chaining, negative testing, response validation, and data-driven testing.

The project uses the DummyJSON Products API to practice real-world API testing scenarios and validate API responses.

## Tools and Technologies

- **API Testing Tool:** Postman
- **Programming Language:** JavaScript
- **Test Execution:** Postman Collection Runner
- **Test Data Management:** Environment Variables
- **API:** DummyJSON Products API
- **HTTP Methods:** GET (product retrieval and validation scenarios)

## Project Objectives

- Validate HTTP response status codes.
- Verify response body fields and data types.
- Implement dynamic API request chaining.
- Store and reuse API response values using environment variables.
- Perform negative testing for invalid product IDs.
- Validate error responses and error messages.
- Execute data-driven tests using multiple product IDs.
- Automate test execution using Postman Collection Runner.

## Key Test Scenarios

### 1. Product Details Validation
- Verify successful product retrieval.
- Validate product title, price, rating, and stock.
- Check required fields and expected data types.

### 2. Dynamic API Request Chaining
- Retrieve product details.
- Save the product ID and title in environment variables.
- Reuse the saved product ID in a subsequent request.
- Compare the returned product ID and title against the saved values.

### 3. Negative Testing
- Send requests using invalid product IDs.
- Verify the expected HTTP 404 response.
- Validate the returned error message.

### 4. API Response Structure Validation
- Verify required response fields.
- Validate data types and field presence.
- Check the structure of the product response.

### 5. Data-Driven API Testing
- Execute product validation scenarios for multiple product IDs.
- Validate successful responses for existing products.
- Check expected error responses for nonexistent products.

## Execution and Results

The following results were observed in Postman during project verification:

| Test Run | Passed Checks | Failed Checks |
|---|---:|---:|
| Task 11: Dynamic Request Chaining | 2 | 0 |
| Tasks 12–15: Product Validation, Negative Testing, Response Structure and Data-Driven Testing | 30 | 0 |

**Latest recorded result:** 30 passed, 0 failed, and 0 errors for the Tasks 12–15 collection run.

## How to Run the Project

1. Open Postman.
2. Import the project collection if an exported collection file is available.
3. Select the appropriate environment and verify the required variables.
4. Open the collection and run the requests using Collection Runner.
5. Review the response status codes, assertion results, and execution summary.

## Skills Demonstrated

- REST API Testing
- HTTP Status Code Validation
- JavaScript Assertions
- Postman Scripts
- Environment Variables
- Dynamic Request Chaining
- Positive and Negative Testing
- Response Schema and Data Type Validation
- Data-Driven Testing
- Collection Runner Execution

## Learning Outcome

This project demonstrates practical experience in API testing, response validation, dynamic data handling, and automated test execution using Postman.
