Smart Study Planner & Optimizer:


OVERVIEW
This project is a Dynamic Programming-based Study Planner that helps students optimize their study schedule within limited available time.

It uses the 0/1 Knapsack Algorithm to select the best combination of subjects based on:
- Priority
- Difficulty
- Study hours
- Deadlines



FEATURES
- Optimal Study Selection using Dynamic Programming
- Time Constraint Handling (limited study hours)
- Priority & Difficulty Weighting
- Deadline Awareness
- Benefit Score Calculation
- Schedule Generation
- Add / Remove Subjects



ALGORITHM USED

0/1 Knapsack (Dynamic Programming)

Each subject:
Weight = Study Hours
Value = Benefit Score

Goal:
Maximize benefit within limited time

Benefit Formula:
Benefit = (Priority * 30) + (Difficulty * 15)



HOW IT WORKS

1. User adds subjects:
   - Name
   - Study hours
   - Priority
   - Difficulty
   - Deadline

2. System applies Dynamic Programming
3. Selects best subjects
4. Displays:
   - Study plan
   - Skipped subjects
   - Time usage
   - Efficiency



PROJECT STRUCTURE

codingskills-2/

index.html
style.css
script.js
README.txt



HOW TO RUN

1. Download project
2. Open folder
3. Double click index.html



OUTPUT

- Best subject combination
- Study order
- Skipped subjects
- Efficiency percentage


CONCEPTS USED

- Dynamic Programming
- 0/1 Knapsack
- Optimization

--------------------------------

USE CASES

- Study planning
- Time management
- Task optimization

--------------------------------

FUTURE IMPROVEMENTS

- Better UI
- Graphs
- AI suggestions
- Data storage

--------------------------------

AUTHOR

Archana
Kamali


If you like this project, give it a star on GitHub.
