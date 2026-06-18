# Test Scenarios

| Scenario ID | Module | Test Scenario | Priority |
| --- | --- | --- | --- |
| TS_API_001 | Authentication | Validate login API behavior for valid and invalid credentials | High |
| TS_API_002 | Authentication | Validate registration API for successful and missing-field combinations | High |
| TS_API_003 | Authentication | Validate token generation and environment variable capture | High |
| TS_API_004 | User API | Validate user retrieval by valid user id | High |
| TS_API_005 | User API | Validate paginated user list response and metadata | Medium |
| TS_API_006 | User API | Validate create user response body, id, and timestamp | High |
| TS_API_007 | User API | Validate full user update using PUT | Medium |
| TS_API_008 | User API | Validate partial user update using PATCH | Medium |
| TS_API_009 | User API | Validate delete user no-content response | High |
| TS_API_010 | Negative Testing | Validate not found behavior for invalid user id | High |
| TS_API_011 | Negative Testing | Validate unsupported endpoint response | Medium |
| TS_API_012 | Negative Testing | Validate invalid payload handling and defect reporting | High |
| TS_API_013 | Negative Testing | Validate empty request body behavior for mandatory fields | High |
| TS_API_014 | Smoke Testing | Validate critical API availability before regression execution | Critical |
| TS_API_015 | Regression Testing | Validate positive, negative, and edge scenarios before release | Critical |
| TS_API_016 | Performance Guardrail | Validate response time is below 1000 ms for critical endpoints | Medium |
