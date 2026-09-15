# CMP 262 – Data Science Programming

## Week 3 – Lab 1: Python Lists and Tuples

**Due:**  
**Points: 100**

## Purpose

This lab gives you practice working with Python **lists** and **tuples**. You will create collections, access values, modify lists, use common functions, loop through lists, and compare mutable and immutable data structures.

Complete all work in the Jupyter Notebook provided in this repository:

`ListsAndTuples.ipynb`

Add a **Markdown heading before each part** and complete each requirement in your own code.

---

## Part 1 – Creating and Accessing a List

Create a list named `courses` containing at least **five course names**.

Display:

- The entire list
- The first course
- The third course
- The last course
- The number of courses using `len()`

Then display the **first three courses** using slicing.

**Points: 15**

---

## Part 2 – Modifying a List

Create a list named `favorite_foods` containing at least **four foods**.

Complete the following:

1. Display the original list.
2. Change one food using its index.
3. Add a new food using `append()`.
4. Remove one food using `remove()`.
5. Display the updated list.

**Points: 15**

---

## Part 3 – Working with Numbers

Create a list named `scores` containing at least **six numbers**.

Display:

- The entire list
- The highest score using `max()`
- The lowest score using `min()`
- The total using `sum()`
- The number of scores using `len()`
- The average score

Use the following calculation for the average:

`sum(scores) / len(scores)`

**Points: 20**

---

## Part 4 – Looping Through a List

Create a list named `cities` containing at least **five cities**.

Use a `for` loop to display each city on a separate line.

Then use another `for` loop to display a message for each city in this format:

`I would like to visit CITY.`

Replace `CITY` with the city from the list.

**Points: 15**

---

## Part 5 – Tuples

Create a tuple named `student_record` containing:

- Student name
- Major
- Graduation year
- GPA

Display:

- The entire tuple
- The student's name
- The student's major
- The graduation year
- The GPA
- The number of values using `len()`

Then answer the following question in a **Markdown cell**:

**Why can you change values in a list but not in a tuple?**

**Points: 15**

---

## Part 6 – Lists vs. Tuples

In a **Markdown cell**, answer the following questions in your own words:

1. What is a list?
2. What is a tuple?
3. What is one similarity between a list and a tuple?
4. What is the main difference between them?
5. What does **mutable** mean?
6. Which is mutable: a list or a tuple?

**Points: 10**

---

## Part 7 – Challenge: Student Scores

Use the following list:

```python
student_scores = [78, 92, 85, 67, 95, 88, 73]
```

Write Python code that:

1. Displays the highest score.
2. Displays the lowest score.
3. Calculates and displays the average score.
4. Uses a `for` loop to display only scores that are **80 or higher**.
5. Counts how many scores are **80 or higher**.

### Challenge Rule

Try to solve this part using the concepts covered in class.

Do not manually print individual scores.

**Points: 10**

---

## Before You Submit

Make sure that:

- Every required part is complete.
- Every part has a Markdown heading.
- All notebook cells have been run.
- All required output is visible.
- There are no Python errors.
- Your notebook is saved as `ListsAndTuples.ipynb`.
- You completed `AI-Use-Report.md` honestly.
- Your latest work has been committed and pushed to GitHub.

## Submission

Submit the link to **your own completed GitHub repository** through Blackboard Ultra.

## Important

- Write your own code.
- Use clear variable names.
- Test each section before moving to the next one.
- You should be able to explain every line of code you submit.
- Follow the rules in `AI-Use-Policy.md`.

## Grading Summary

| Section | Points |
|---|---:|
| Creating and Accessing a List | 15 |
| Modifying a List | 15 |
| Working with Numbers | 20 |
| Looping Through a List | 15 |
| Tuples | 15 |
| Lists vs. Tuples | 10 |
| Challenge: Student Scores | 10 |
| **Total** | **100** |
