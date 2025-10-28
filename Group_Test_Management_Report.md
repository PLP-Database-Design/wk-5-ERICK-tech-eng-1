# 🧪 Group Test Management Report - Word Puzzle Game Plus

**Course:** Software Testing & Quality Assurance  
**Module:** Test Management (Week 5)  
**Team:** Alex Johnson, Sarah Chen, Mike Rodriguez  
**Submission Date:** October 28, 2025

## 1. Project Overview

Word Puzzle Game Plus is a browser-based word puzzle game designed to enhance user engagement through scoring, hints, bonus rounds, and a leaderboard. This report summarizes test management practices, risk analysis, test execution, and defect logging.

## 2. Test Objectives

- Verify game features function correctly.
- Detect and document defects.
- Assess risk coverage through structured testing.
- Measure quality through metrics like pass rate and defect density.

## 3. Test Scope

- **In Scope:** Reset game, leaderboard, bonus round, hint system, input validation.
- **Out of Scope:** Multiplayer mode, user authentication (not implemented in current version).

## 4. Team Roles

| Role          | Name         | Responsibilities                                   |
| ------------- | ------------ | -------------------------------------------------- |
| Test Manager  | Erick Omondi | Test planning, schedule, metrics tracking          |
| Risk Analyst  | Henok Girma  | Risk analysis, test design, risk coverage          |
| Test Executor | Lydiah Awour | Execute tests, defect logging, evidence collection |

## 5. Risk Analysis

| Risk ID | Description                    | Severity | Mitigation                                               |
| ------- | ------------------------------ | -------- | -------------------------------------------------------- |
| R1      | Data corruption in leaderboard | High     | Validate leaderboard updates, backup localStorage        |
| R2      | Bonus round logic errors       | High     | Execute bonus rounds thoroughly, track score doubling    |
| R3      | Accidental reset               | Medium   | Confirm reset button functionality with warnings         |
| R4      | Input validation errors        | Medium   | Test invalid/empty inputs thoroughly                     |
| R5      | UI message persistence         | Low      | Adjust timing for bonus/feedback messages                |
| R6      | Storage limits                 | Low      | Monitor localStorage limits, implement overflow handling |

## 6. Test Cases Summary

- Total Test Cases: 8
- Risk-Based: 5
- Negative: 2
- Usability: 1
- Pass Rate: 100%

## 7. Metrics

| Metric              | Value | Calculation              |
| ------------------- | ----- | ------------------------ |
| Test Case Pass Rate | 100%  | 8/8                      |
| Defect Density      | 0.375 | 3 defects / 8 test cases |
| Risk Coverage       | 100%  | 6/6 risks addressed      |

## 8. Critical Findings

1. Hint cost bug — deduction fails when score < 2
2. Leaderboard duplication — multiple identical entries possible
3. Bonus round message persistence — may display too long

## 9. Reflection & Lessons Learned

- Effective team collaboration improves test coverage.
- Risk-based testing identifies high-impact defects efficiently.
- Metrics provide a clear measure of project quality.
- Proper GitHub issue tracking ensures transparent defect management.

## 10. Conclusion

The Word Puzzle Game Plus application was thoroughly tested, all planned test cases executed, risks addressed, and defects documented. This project demonstrates solid test management practices applied in a real-world scenario.
