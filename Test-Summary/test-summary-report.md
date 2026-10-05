# Test Summary Report

## Project

Flight Booking Application – Manual QA

## Test Scope

Flight search, flight results, flight selection, passenger details, payment, booking confirmation and end-to-end booking flow.

## Test Environment

* Browser: Google Chrome
* OS: Windows
* URL: https://qapractice.com/flight-booking-scenarios

## Execution Summary

* Total Test Cases: 29
* Executed: 29
* Passed: 26
* Failed: 3
* Blocked: 0
* Not Executed: 0

## Defect Summary

* Critical: 0
* High: 0
* Medium: 3
* Low: 0

## Key Findings

\- The core flight search and booking workflow was successfully completed.

\- Flight selection, passenger details and booking confirmation worked as expected.

\- The application accepted an invalid/short card number during payment.

\- The application accepted an expired card expiry date during payment.

\- The application accepted an invalid/short CVV during payment.

\- Payment validation requires improvement for invalid card information.

## Limitations

This is a practice application. Real production payment processing, production infrastructure, load testing, penetration testing and inaccessible backend/database validation are outside the project scope.

## Final Assessment

The application successfully supports the primary flight booking workflow from flight search through booking confirmation. However, payment validation defects were identified during negative testing. The identified issues should be addressed before considering the application production-ready.

