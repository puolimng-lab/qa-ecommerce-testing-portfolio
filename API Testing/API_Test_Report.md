# API Test Report

## Project Information

**Project Name:** E-Commerce API Testing  
**Testing Tool:** Postman  
**API Type:** REST API  
**Test Environment:** Fake Store API (https://fakestoreapi.com)

---

## Test Objective

The objective of this testing is to verify that the API endpoints function correctly by validating response status codes, response data, response time, and expected business behavior.

---

## API Test Summary

| Test ID | API Endpoint | Method | Test Scenario | Expected Result | Actual Result | Status |
|---------|-------------|--------|--------------|----------------|---------------|--------|
| API_001 | /products | GET | Retrieve all products | Return a list of products with HTTP 200 response | Product list returned successfully with status code 200 | Passed |
| API_002 | /products/1 | GET | Retrieve a specific product by ID | Return product details with HTTP 200 response | Product details returned successfully with correct product ID | Passed |
| API_003 | /auth/login | POST | Login using valid credentials | Return authentication token with HTTP 200 response | Token returned successfully after authentication | Passed |

---

## Validation Performed

### Response Validation
- Verified HTTP status codes.
- Verified response data structure.
- Verified required fields in JSON responses.

### Performance Validation
- Verified API response time is within acceptable range.

### Business Validation
- Verified product information is returned correctly.
- Verified successful user authentication returns a valid token.

---

## Defects Found

No critical defects were identified during the API testing execution.

---

## Conclusion

The tested API endpoints are functioning as expected. The API responses, performance, and returned data meet the defined testing requirements.
