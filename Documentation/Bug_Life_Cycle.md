# Bug Life Cycle

The bug life cycle describes how a defect moves from discovery to closure.

## Common States
| State | Meaning |
| --- | --- |
| New | Defect is logged by QA for review. |
| Assigned | Defect is assigned to a developer or team. |
| Open | Developer accepts the defect for investigation. |
| Fixed | Developer has implemented a fix. |
| Retest | QA validates the fix in the target environment. |
| Verified | QA confirms the issue is resolved. |
| Closed | Defect is completed and no further action is required. |
| Reopened | Issue still exists after the fix and is sent back. |
| Deferred | Fix is postponed to a future release. |
| Rejected | Defect is invalid, duplicate, or expected behavior. |

## Severity vs Priority
Severity describes business or technical impact. Priority describes how quickly the team should fix it. A high-severity production blocker is usually high priority, while a low-severity UI typo may be lower priority.

## Good Bug Report Qualities
A good bug report is reproducible, specific, evidence-backed, and includes environment details, test data, expected result, actual result, and clear impact.
