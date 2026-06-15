# Test Execution Report

## Project Information

**Project Name:** E-Commerce Web Application Testing  
**Testing Type:** Manual Testing & API Testing  
**Testing Period:** Sample Test Cycle  
**Tester:** Ng Puo Lim  
**Testing Tools:** Google Sheets, Postman, GitHub

---

## Test Scope

The following modules were included in the testing scope:

- User Login
- User Registration
- Shopping Cart
- Checkout Process
- Payment Workflow
- REST API Endpoints

---

## Test Case Execution Summary

| Module | Total Test Cases | Passed | Failed | Blocked |
|---------|-----------------|--------|--------|---------|
| Login | 15 | 14 | 1 | 0 |
| Registration | 15 | 14 | 1 | 0 |
| Shopping Cart & Checkout | 20 | 17 | 3 | 0 |
| API Testing | 3 | 3 | 0 | 0 |
| **Total** | **53** | **48** | **5** | **0** |

---

## Defect Summary

The following defects were identified during testing:

| Bug ID | Description | Severity | Status |
|--------|-------------|----------|--------|
| BUG-001 | Login button does not respond after clicking | High | Open |
| BUG-002 | Incorrect shopping cart total calculation | High | Open |
| BUG-003 | Registration allows duplicate email | Medium | Open |
| BUG-004 | Checkout accepts invalid phone number | Medium | Open |
| BUG-005 | Multiple payment submissions create duplicate orders | Critical | Open |

---

## Testing Coverage

The testing covered the following areas:

### Functional Testing
- Login and registration workflow
- Shopping cart operations
- Checkout and payment process

### Validation Testing
- Required field validation
- Input format validation
- Business rule validation

### Security Testing
- SQL injection prevention
- Session handling
- Duplicate transaction prevention

### API Testing
- HTTP response validation
- JSON response validation
- Response time verification

---

## Test Conclusion

A total of 53 test cases were executed during the testing cycle.  
48 test cases passed and 5 test cases failed due to identified application defects.

The application provides the core functionality required for an e-commerce system. However, several high and critical severity issues were identified, particularly in authentication, shopping cart calculation, and payment processing.

It is recommended that all high and critical defects be resolved and re-tested before production release.

---

## Recommendation

Current Release Status: **Not Ready for Production**

Reason:
- Critical payment issue may create duplicate customer orders.
- High severity issues impact core user functionality.
- Defects should be fixed and validated through regression testing before release.
