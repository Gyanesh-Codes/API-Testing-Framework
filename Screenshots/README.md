# Test Execution Screenshots

This folder contains Postman Collection Runner evidence captured after executing the API Testing & Validation Framework.

## Evidence Files

| File | Test Suite | Evidence |
| --- | --- | --- |
| `01_smoke_testing_passed.png` | Smoke Testing | Login, registration, and user retrieval smoke checks passed successfully with 0 errors. |
| `02_authentication_testing_passed.png` | Authentication Testing | Login and registration positive and negative authentication validations passed with 0 errors. |
| `03_user_api_testing_passed.png` | User API Testing | User retrieval, list, create, update, delete, and not found API validations passed with 0 errors. |
| `04_negative_testing_defects.png` | Negative Testing | Negative testing identified failed validations for invalid endpoint handling and unauthorized access behavior. |

## QA Interpretation

The positive smoke, authentication, and user API suites passed, confirming that the core API workflows are stable. The negative testing run produced expected validation failures, which are documented as defect evidence in the `Bug_Reports` folder.
