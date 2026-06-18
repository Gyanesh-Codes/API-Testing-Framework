# BUG_API_003: Invalid endpoint does not return standardized error body

| Field | Details |
| --- | --- |
| Bug ID | BUG_API_003 |
| Title | Invalid endpoint does not return standardized error body |
| Severity | Low |
| Priority | P3 |
| Environment | https://reqres.in with Postman collection |
| Steps To Reproduce | 1. Send GET /api/invalid-endpoint<br>2. Check response structure |
| Expected Result | 404 response should include consistent error code/message for client debugging |
| Actual Result | Response body is empty or inconsistent, reducing diagnosability |
| Status | Open |
| Assigned To | API Platform Team |

## QA Notes
This defect is included to demonstrate practical defect management, severity and priority classification, reproducible steps, and interview-ready API validation reasoning.
