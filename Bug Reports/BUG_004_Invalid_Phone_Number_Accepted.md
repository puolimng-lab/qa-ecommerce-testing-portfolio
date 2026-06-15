# BUG-004: Checkout Accepts Invalid Phone Number Format

## Environment
- Browser: Google Chrome
- Operating System: Windows 11

## Severity
Medium

## Priority
Medium

## Preconditions
User has items in the shopping cart and proceeds to checkout.

## Steps to Reproduce
1. Enter invalid characters in the phone number field.
2. Complete the checkout process.

## Test Data
Phone Number: ABC123

## Expected Result
The system should reject invalid phone number formats and display a validation message.

## Actual Result
The system accepts the invalid phone number and allows the order to proceed.

## Status
Open 
