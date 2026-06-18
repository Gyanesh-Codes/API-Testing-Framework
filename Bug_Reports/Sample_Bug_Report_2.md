# BUG_API_002: Create User API accepts invalid data types

| Field | Details |
| --- | --- |
| Bug ID | BUG_API_002 |
| Title | Create User API accepts invalid data types |
| Severity | Medium |
| Priority | P2 |
| Environment | https://reqres.in with Postman collection |
| Steps To Reproduce | 1. Send POST /api/users with name as number and job as null<br>2. Observe response |
| Expected Result | API should reject invalid schema with 400 validation error |
| Actual Result | API accepts invalid field types and creates a record-like response |
| Status | Open |
| Assigned To | API Developer |

## QA Notes
This defect is included to demonstrate practical defect management, severity and priority classification, reproducible steps, and interview-ready API validation reasoning.
