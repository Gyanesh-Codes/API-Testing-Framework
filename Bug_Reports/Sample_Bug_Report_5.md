# BUG_API_005: Unauthorized request behavior depends on API key configuration

| Field | Details |
| --- | --- |
| Bug ID | BUG_API_005 |
| Title | Unauthorized request behavior depends on API key configuration |
| Severity | High |
| Priority | P1 |
| Environment | https://reqres.in with Postman collection |
| Steps To Reproduce | 1. Remove x-api-key header<br>2. Send GET /api/users/2<br>3. Observe status code |
| Expected Result | API should consistently return 401 or 403 with authorization error |
| Actual Result | Authorization behavior requires live key setup validation and may block CI runs if not configured |
| Status | Blocked |
| Assigned To | QA Automation Engineer |

## QA Notes
This defect is included to demonstrate practical defect management, severity and priority classification, reproducible steps, and interview-ready API validation reasoning.
