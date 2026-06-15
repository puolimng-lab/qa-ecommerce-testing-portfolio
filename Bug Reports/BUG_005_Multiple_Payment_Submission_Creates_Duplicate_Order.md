# BUG-005: Multiple Payment Clicks Create Duplicate Orders

## Environment
- Browser: Google Chrome
- Operating System: Windows 11

## Severity
Critical

## Priority
High

## Preconditions
User has completed the checkout information and is on the payment page.

## Steps to Reproduce
1. Enter valid payment information.
2. Click the payment button repeatedly.

## Expected Result
The system should prevent duplicate payment requests and create only one order.

## Actual Result
Multiple orders are created from repeated payment submissions.

## Status
Open
