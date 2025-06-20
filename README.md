# 🏏 Cricket Scorecard Management System

This is a **C language console application** that records and displays details of a cricket match including batsmen and bowlers' performances. It features a basic text menu that allows users to input data, retrieve stats, and generate match summaries.

## 🔹 Features

- Input details for up to 11 batsmen and 11 bowlers.
- Records:
  - Runs from 1s, 2s, 3s, 4s, and 6s.
  - Balls faced by batsmen.
  - Overs bowled, runs given, and wickets taken by bowlers.
- Calculates:
  - Total runs.
  - Strike rate.
  - Economy rate.
- Menu options:
  - Batsman detail.
  - Bowler detail.
  - Match summary.
  - Top performances record.
  - Exit.

## 📸 Screenshots

### 🎯 Batsman Input & Output
![Batsman input](./Screenshots/Screenshot%202025-06-20%20174615.png)
![Batsman summary](./Screenshots/Screenshot%202025-06-20%20174723.png)

### 🎯 Bowler Input & Output
![Bowler input](./Screenshots/Screenshot%202025-06-20%20174624.png)
![Bowler summary](./Screenshots/Screenshot%202025-06-20%20174700.png)

### 🧾 Match Summary
![Match summary](./Screenshots/Screenshot%202025-06-20%20174734.png)

## 🛠️ How to Compile & Run

```bash
gcc cricket_scorecard.c -o scorecard
./scorecard
