# qa-practice-assessment
Practice repo for Speechify QA assessment prep

## Test Cases - Speechify Speed Control

| Test Case | Input | Expected Result |
|-----------|-------|-----------------|
| Valid minimum speed | 0.5x | Accepted |
| Just below minimum | 0.4x | Rejected |
| Valid maximum speed | 4.5x | Accepted |
| Just above maximum | 4.6x | Rejected |
| Negative value | -1x | Rejected |
