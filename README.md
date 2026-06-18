# API Testing & Validation Framework

## Project Overview
API Testing & Validation Framework is a GitHub-ready SDET portfolio project that demonstrates REST API testing, Postman automation, regression testing, smoke testing, negative testing, defect documentation, and QA process knowledge using the public ReqRes API.

ReqRes currently documents that requests require an `x-api-key` header, so this project uses a Postman environment variable named `apiKey` instead of hardcoding credentials.

## Features
- Postman collection with modular folders for authentication, user APIs, negative testing, smoke testing, and regression testing.
- JavaScript test scripts for status code, response time, response body, response structure, required fields, error messages, and token validation.
- Detailed manual and automation-ready test cases in Markdown and Excel.
- Professional test scenarios, bug reports, test execution report, and regression report.
- Beginner-friendly QA documentation covering SDLC, STLC, Agile, Scrum, bug life cycle, API testing, smoke testing, regression testing, functional testing, and exploratory testing.

## Tech Stack
- Postman
- JavaScript Postman test scripts
- REST APIs
- ReqRes public API
- Git and GitHub
- Optional execution with Newman

## Folder Structure
```text
API-Testing-Framework/
|-- README.md
|-- Postman_Collection/
|   |-- SDET_API_Testing_Framework.postman_collection.json
|   |-- Environment.postman_environment.json
|-- Test_Cases/
|   |-- Test_Cases.xlsx
|   |-- Test_Cases.md
|-- Test_Scenarios/
|   |-- Test_Scenarios.md
|-- Bug_Reports/
|   |-- Sample_Bug_Report_1.md
|   |-- Sample_Bug_Report_2.md
|   |-- Sample_Bug_Report_3.md
|   |-- Sample_Bug_Report_4.md
|   |-- Sample_Bug_Report_5.md
|-- Reports/
|   |-- Test_Execution_Report.md
|   |-- Regression_Report.md
|-- Screenshots/
|   |-- Placeholder_Instructions.md
|-- Documentation/
|   |-- SDLC_Overview.md
|   |-- STLC_Overview.md
|   |-- Bug_Life_Cycle.md
|   |-- API_Testing_Strategy.md
```

## Testing Strategy
The strategy combines requirement analysis, scenario design, positive testing, negative testing, smoke testing, regression testing, exploratory validation, and defect reporting. Each API request includes automated assertions so failures can be quickly mapped to expected behavior, response schema, or business rule gaps.

## API Coverage
- Authentication: login, registration, missing password, missing email, invalid credentials.
- Users: get single user, get user list, create user, update user, delete user, not found user.
- Negative testing: invalid endpoint, invalid payload, empty body, invalid id, unauthorized access, missing mandatory fields.
- Smoke testing: login, registration, and user retrieval.
- Regression testing: critical positive workflows, negative scenarios, and edge cases.

## Test Case Coverage
This project includes 22 detailed test cases covering authentication, user APIs, negative testing, smoke testing, regression testing, response validation, and defect discovery.

## Bug Tracking Approach
Defects are documented with severity, priority, environment, steps to reproduce, expected result, actual result, status, and assigned owner. The format is intentionally similar to Jira-style defect reporting so it can be discussed as part of Agile Scrum QA workflow.

## How To Run
1. Import `Postman_Collection/SDET_API_Testing_Framework.postman_collection.json` into Postman.
2. Import `Postman_Collection/Environment.postman_environment.json`.
3. Get a ReqRes API key from the ReqRes dashboard and replace `YOUR_REQRES_API_KEY` in the `apiKey` environment variable.
4. Select the imported environment.
5. Run individual requests or use Collection Runner for Smoke Testing and Regression Testing folders.

## Future Improvements
- Add Newman HTML reports in CI.
- Add GitHub Actions workflow for scheduled regression execution.
- Add SQL validation examples for database-backed APIs.
- Add contract testing using OpenAPI schema validation.
- Add Jira export examples for defect management.

**KEY-POINTS:**
- Designed and executed API Testing and Automation Testing workflows for REST APIs using Postman JavaScript assertions, validating status codes, response time, response body, schema fields, authentication tokens, and error messages.
- Created 20+ Test Cases, 15+ Test Scenarios, Smoke Testing suite, Regression Testing suite, and Bug Tracking documentation aligned with SDLC, STLC, Agile, Scrum, QA, SDET, and Software Testing methodologies.
- Documented realistic defect reports and validation evidence to demonstrate Software Quality Assurance, Defect Management, functional testing, negative testing, and release readiness analysis.
