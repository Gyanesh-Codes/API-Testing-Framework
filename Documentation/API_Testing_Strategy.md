# API Testing Strategy

## Objective
Validate ReqRes REST APIs for correctness, reliability, error handling, response schema, performance guardrails, and regression stability.

## Scope
- Authentication APIs: login and registration.
- User APIs: retrieve, create, update, delete, and not found flows.
- Negative APIs: invalid endpoint, invalid body, empty body, invalid id, unauthorized access, missing mandatory fields.
- Smoke suite: critical availability checks.
- Regression suite: positive, negative, and edge workflows.

## Validation Checklist
- HTTP status code matches expected behavior.
- Response time is below 1000 ms.
- Response body is valid JSON when expected.
- Required fields exist and have expected data types.
- Error messages are meaningful for negative scenarios.
- Authentication token exists for successful auth flows.
- No-content responses return empty bodies.

## Test Data
Stable public test data is used where available, such as `eve.holt@reqres.in`, `cityslicka`, `pistol`, and user id `2`. Environment variables are used for `baseUrl`, `apiKey`, `userId`, response time SLA, and captured auth tokens.

## Entry Criteria
- Postman collection and environment are imported.
- Valid ReqRes API key is configured.
- Network access to ReqRes is available.
- Test data and environment variables are reviewed.

## Exit Criteria
- Smoke tests pass.
- Regression results are documented.
- Failed and blocked tests are linked to defect reports.
- High severity defects are reviewed before release recommendation.
