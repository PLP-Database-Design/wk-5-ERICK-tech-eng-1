# 🧪 Final Group Test Report Template — Word Puzzle Game Plus

**Level:** Intermediate QA | **Week 5:** Test Management

**Course:** Software Testing & Quality Assurance  
**Module:** Test Management (Week 5)  
**Project Type:** Group Assessment  
**Submission Date:** 2025-10-28

📁 Project Structure
group-test-management/
│
├── 📄 README.md # This file
├── 📊 Group_Test_Management_Report.md # Main report document
├── 🐛 github-issues/ # Defect evidence
│ ├── issue-1-hint-cost-bug.md
│ ├── issue-2-leaderboard-duplicate.md
│ └── issue-3-bonus-message-persist.md
├── 📋 test-cases/ # Detailed test cases
│ └── detailed-test-cases.md
└── 🖼️ screenshots/ # Evidence screenshots
├── test-execution-evidence.png
├── defect-evidence-1.png
└── defect-evidence-2.png

## 👥 Team Roles & Responsibilities

Role Name Key Deliverables
Test Manager Erick Omondi Test Plan, Schedule, Metrics Tracking, Final Report
Risk Analyst Henok Girma Risk Analysis, Test Design, Risk Coverage
Test Executor Lydiah Awour Test Execution, Defect Logging, Evidence Collection

## 🎯 Assignment Requirements Checklist

## ✅ Mandatory Requirements

Team of exactly 3 members - No duplicate membership
Single combined report - Group_Test_Management_Report.md
Test Plan with objectives, scope, resources, schedule
Risk Analysis with at least 6 prioritized risks
Minimum 8 test cases (≥5 risk-based, 2 negative, 1 usability)
At least 3 defects logged on GitHub Issues
Test monitoring metrics with calculations
Reflection section with lessons learned

## ✅ GitHub Issues Requirements

Each defect includes:

Clear title and description
Steps to reproduce
Expected vs Actual results
Severity level
Risk impact mapping
Screenshot evidence

## 🕹️ System Under Test

Word Puzzle Game Plus — A browser-based word puzzle game with enhanced features.

Key Features Tested:
Reset Game — Instant score and progress reset
Leaderboard — Top 3 scores persistence in localStorage
Bonus Round — Score doubling every 3 puzzles
Hint System — Point deduction for assistance
Input Validation — User input handling

## 📊 Key Metrics Summary

Metric Value Calculation
Test Case Pass Rate 100% 8/8 test cases passed
Defect Density 0.375 3 defects / 8 test cases
Risk Coverage 100% 6/6 risks covered
Critical Defects 0 No high-severity issues found

## 🚨 Critical Findings

Hint Cost Bug — Hint deduction fails when score < 2
Leaderboard Duplication — Potential for duplicate score entries
UI Message Timing — Bonus message timing conflicts

## 📈 Risk Analysis Highlights

High Priority Risks: Data corruption (R1), Bonus logic errors (R2)
Medium Priority: Accidental reset (R3), Input validation (R4)
Low Priority: UI state issues (R5), Storage limits (R6)

## 🔗 GitHub Issues Created

[Issue #1] Hint cost not properly deducted when score < 2
[Issue #2] Leaderboard displays duplicate scores
[Issue #3] Bonus round message persists too long

## 📝 Submission Instructions

What to Submit:
This README.md file
Group_Test_Management_Report.md (main report)
GitHub issue links (minimum of 3)
Supporting evidence files
How to Submit:
One submission per group via the learning platform
Include all team members' names clearly
Add links to actual GitHub issues
Ensure no team member appears in multiple groups

## 🎓 Learning Outcomes Demonstrated

✅ Test Planning — Comprehensive test strategy development
✅ Risk-Based Testing — Priority-driven test execution
✅ Defect Management — Professional issue tracking
✅ Team Collaboration — Effective role-based workflow
✅ Metrics & Reporting — Data-driven quality assessment

## 📞 Contact Information

Test Manager: Erick Omondi Risk Analyst: Henok Girma Test Executor: Lydiah Awour
