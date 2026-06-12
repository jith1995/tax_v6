# CA Review Notes

This MVP is intended for feedback on user journey, logic structure, and missing tax-rule scenarios.

## Current assumptions in the MVP

- FD and bank interest are treated separately from capital gains as interest income.
- Capital gains are split into equity, equity mutual funds, debt/other mutual funds, property, gold/other assets, ESOP/RSU, and crypto/VDA.
- Some special capital gains rates are included as preview logic.
- The old/new regime comparison is directional and requires validation against the latest applicable Finance Act and ITR instructions.
- Deductions are structured into 80C, NPS, medical insurance, housing, donations, education loan interest, savings interest, and other deductions.

## Feedback requested from CA

1. Which income types are missing?
2. Which deduction fields should be added or removed?
3. Are the ITR form selection rules correct for common cases?
4. Are the old vs new regime assumptions correct?
5. Are capital gains categories sufficient for the first public version?
6. Which cases should be blocked and moved to assisted filing?
7. What disclaimers should be visible to users?

## Product principle

The tool should explain the calculation, not just show a number. Every major output should answer:

- What is the result?
- Why did the system choose it?
- Which rule or input caused it?
- What documents are needed next?
