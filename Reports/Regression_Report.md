# Regression Report

## Regression Scope
Regression testing covers authentication, user retrieval, user creation, user update, user deletion, not found behavior, invalid payloads, empty bodies, and missing mandatory fields.

## Regression Suite
| Area | Covered APIs | Result |
| --- | --- | --- |
| Authentication | POST /api/login, POST /api/register | Passed with valid data; negative cases validated |
| User Retrieval | GET /api/users, GET /api/users/{id} | Passed |
| User Mutation | POST /api/users, PUT /api/users/{id}, DELETE /api/users/{id} | Passed with documented validation gaps |
| Negative Testing | Invalid endpoint, invalid id, missing fields, unauthorized access | Failed/Blocked items documented as defects |

## Risks
- Public API behavior may change or require account-level API key configuration.
- Demo APIs may not enforce all business validation rules expected in production systems.
- CI execution should include retry or rate-limit handling for public endpoints.

## Recommendation
Regression suite can be used for portfolio demonstration after configuring a valid ReqRes API key. Defects should be discussed as examples of QA analysis rather than production blockers owned by this project.
