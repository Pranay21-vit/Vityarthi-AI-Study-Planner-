# Vityarthi-AI-Study-Planner-

# AI Study Planner (CLI-Based)

## Overview

AI Study Planner is a command-line application designed to help students generate an optimized daily study schedule based on subject priority.

The system calculates priority using three factors:

* Difficulty level
* Importance of the subject
* Days remaining until the exam

Based on this, study hours are distributed proportionally among subjects.

---

## Features

* Priority-based study scheduling
* Weighted calculation model
* Deadline-aware planning
* Simple command-line interface
* No external dependencies

---

## Technologies Used

* Python 3
* Object-Oriented Programming (OOP)
* Command Line Interface (CLI)

---

## Project Structure

```
AI_Study_Planner/
│
├── main.py        # Main application file
└── README.md      # Documentation
```

---

## Working Logic

### Input

The user provides:

* Number of subjects
* Subject name
* Difficulty (1–5)
* Importance (1–5)
* Days left until exam
* Total available study hours per day

### Priority Formula

Priority is calculated using:

```
Priority = (Difficulty × 0.4) + (Importance × 0.4) + ((1 / Days Left) × 0.2)
```

### Time Allocation

* Subjects are sorted by priority in descending order
* Total study time is divided proportionally based on priority scores

---

## How to Run

1. Clone the repository:

```
git clone <your-repo-link>
```

2. Navigate to the project folder:

```
cd AI_Study_Planner
```

3. Run the program:

```
python main.py
```

---

## Example Execution

```
=== AI Study Planner ===

Enter number of subjects: 3

Subject name: Maths
Difficulty (1-5): 5
Importance (1-5): 5
Days until exam: 2

Subject name: Physics
Difficulty (1-5): 4
Importance (1-5): 4
Days until exam: 3

Subject name: English
Difficulty (1-5): 2
Importance (1-5): 3
Days until exam: 5

Total study hours per day: 6

Today's Study Plan:

Maths: 2.8 hours
Physics: 2.1 hours
English: 1.1 hours
```

---

## Use Cases

* Daily study planning
* Exam preparation strategy
* Time management for students

---

## Future Enhancements

* Graphical User Interface (GUI)
* Weekly and monthly planning
* Calendar integration
* Data storage and tracking
* Machine learning-based recommendations

---

## Author Details

Name: Pranay Kothari
Registration Number: 25BCE10248
College: VIT Bhopal University

---

## License

This project is open-source and available under the MIT License.

---
