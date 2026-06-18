# Test Execution Report

## Build Information
- Project: API Testing & Validation Framework
- API Under Test: https://reqres.in
- Tool: Postman
- Execution Type: Functional, Smoke, Regression, Negative
- Test Environment: ReqRes public API with `x-api-key`

## Execution Summary
| Metric | Count |
| --- | ---: |
| Total Test Cases | 22 |
| Passed | 17 |
| Failed | 4 |
| Blocked | 1 |
| Pass Percentage | 77.27% |

## Defect Summary
| Severity | Count | Notes |
| --- | ---: | --- |
| High | 2 | Empty body accepted; unauthorized behavior requires key validation |
| Medium | 2 | Invalid schema accepted; missing email error specificity |
| Low | 1 | Invalid endpoint lacks standardized error response |

## Exit Criteria
- Smoke test critical APIs must pass before regression execution.
- High severity defects must be reviewed before release sign-off.
- Blocked tests must be re-executed after valid ReqRes API key setup.
