# Detailed Test Cases - Word Puzzle Game Plus

## Test Case 1: Reset Game

- **Objective:** Verify that reset button clears score and progress
- **Input:** Click "Reset"
- **Expected Result:** Score = 0, puzzle cleared
- **Actual Result:** As expected ✅

## Test Case 2: Hint System

- **Objective:** Hint deducts 2 points
- **Input:** Click "Hint" with score >= 2
- **Expected Result:** Hint displayed, score decreased by 2
- **Actual Result:** Works as expected ✅

## Test Case 3: Hint System Negative

- **Objective:** Prevent hint if score < 2
- **Input:** Score = 1 → click "Hint"
- **Expected Result:** Message "Not enough points"
- **Actual Result:** Bug discovered ❌

## Test Case 4: Leaderboard Persistence

- **Objective:** Verify leaderboard saves top 3 scores
- **Input:** Play 3 games, record scores
- **Expected Result:** Top 3 displayed, sorted
- **Actual Result:** Works as expected

## Test Case 5: Leaderboard Duplicate Check

- **Objective:** Detect duplicates
- **Input:** Enter same score multiple times
- **Expected Result:** Only unique or timestamped
- **Actual Result:** Bug found

## Test Case 6: Bonus Round Trigger

- **Objective:** Bonus round doubles score every 3 puzzles
- **Input:** Solve 3 puzzles
- **Expected Result:** Score doubles, message displays
- **Actual Result:** Works

## Test Case 7: Bonus Round Message Timing

- **Objective:** Message persists long enough
- **Input:** Observe bonus round message
- **Expected Result:** Display 4–5 seconds
- **Actual Result:** Bug found

## Test Case 8: Input Validation

- **Objective:** Prevent invalid input submission
- **Input:** Empty string, invalid characters
- **Expected Result:** Reject input, display warning
- **Actual Result:** Works
