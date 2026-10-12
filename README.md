# Python Daily Coding

Focused Python problem-solving practice for data analyst and data engineering roles. This repository contains only daily coding questions and your attempts.

## Structure

```text
python-daily-coding/
├── README.md
├── easy/
├── medium/
└── hard/
```

| Difficulty | Questions |
| --- | --- |
| Easy | [Open easy questions](easy/README.md) |
| Medium | [Open medium questions](medium/README.md) |
| Hard | [Open hard questions](hard/README.md) |

Each question is stored **once**, under its LeetCode difficulty. Easy, medium and hard contain different questions, not three versions of the same question. A retry stays with the original file.

## File names

Use the problem number, padded to four digits, followed by the question name:

```text
easy/0217_contains_duplicate.py
```

The number is the source problem ID, not a daily sequence. There are no date folders. New question files contain the task, source link, example and starter code. The current starter files are intentionally unimplemented.

## Start in VS Code

1. Clone this repository using **Git: Clone**, or open its local folder yourself.
2. Open the assigned numbered file under `easy/`, `medium/` or `hard/`.
3. Write your own attempt, check the examples and edge cases, then submit it to the mentor for review.
4. In **Source Control**, review and stage the question files you changed.
5. Enter a clear commit message, commit, then use **Push** or **Sync Changes**.

When both daily repositories are open, select the matching repository in Source Control before committing. The mentor does not automatically upload your daily solutions.

Example commit: `practice: solve 0217 contains duplicate`

## First prepared questions

| Number | Question file |
| --- | --- |
| 0217 | [Contains Duplicate](easy/0217_contains_duplicate.py) |
| 0242 | [Valid Anagram](easy/0242_valid_anagram.py) |
| 0283 | [Move Zeroes](easy/0283_move_zeroes.py) |

## Run your code

Use Python 3 and the VS Code Python extension. An optional `.venv` keeps dependencies separate. The first questions need only the standard library.

Function stubs raise `NotImplementedError` until you implement them. A file that only defines functions needs you to call those functions with the examples or add your own tests; running the file alone does not test the solution.

## Weekday training

The coding chat runs Monday–Friday at **19:00 Europe/Berlin**, with 3 Python questions. Difficulty increases based on reviewed work, with later recall of earlier questions. Approximately 90 minutes for both languages together is a flexible target.

Questions and starter files can be prepared in the local checkout. Your own reviewed attempts are committed and pushed by you.
