# BUG_API_001: Create User API accepts empty request body

| Field | Details |
| --- | --- |
| Bug ID | BUG_API_001 |
| Title | Create User API accepts empty request body |
| Severity | High |
| Priority | P1 |
| Environment | https://reqres.in with Postman collection |
| Steps To Reproduce | 1. Send POST /api/users with `{}` body<br>2. Observe status and response body |
| Expected Result | API should return 400 Bad Request with mandatory field errors for name and job |
| Actual Result | API returns 201 Created with generated id and createdAt despite missing mandatory fields |
| Status | Open |
| Assigned To | QA Lead / API Team |

## QA Notes
This defect is included to demonstrate practical defect management, severity and priority classification, reproducible steps, and interview-ready API validation reasoning.
