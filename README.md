# Fictional Student Dataset

A Python script that generates a fictional dataset of 200 students.

## Columns
| Column | Description |
|---|---|
| Student ID | Matric number: 26/ for 100L, 25/ for 200L, 24/ for 300L, 23/ for 400L, followed by 5 random digits (e.g. `26/48213`) |
| Department | One of 8 departments |
| Level | 100, 200, 300 or 400 |
| Attendance Percentage | 40 – 100 |
| Average Examination Score | 20 – 100 (loosely correlated with attendance) |

## Usage
```bash
python generate_dataset.py
```
This creates `students.csv`. All data is fictional.
