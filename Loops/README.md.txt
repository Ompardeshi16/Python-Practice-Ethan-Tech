# Loop Practice

This project contains a Python notebook focused on practicing and understanding different types of `for` loops in Python.

## Overview

The exercises in this notebook cover:
- Basic `for` loops using `range()`
- Nested loop structures
- Comparing values across multiple lists
- Simple conditional logic inside loops

## Contents

### 1. Basic Loop with `range()`
This example prints numbers from 1 to 4.

```python
range1 = range(1, 5)

for i in range1:
    print(i)
```

Output:
```python
1
2
3
4
```

---

### 2. Nested `for` Loop
This example checks for matching values between two lists.

```python
List1 = ["Yellow", "Green", "Red"]
List2 = ["Pink", "Orange", "Yellow"]

for i in List1:
    for j in List2:
        if i == j:
            print("Matched: ", i, j)
```

Output:
```python
Matched:  Yellow Yellow
```

---

### 3. Triple Nested `for` Loop
This example checks whether the same value appears in all three lists.

```python
List01 = ["Red", "Yellow", "LightGreen"]
List02 = ["White", "Black", "Yellow"]
List03 = ["White", "Purple", "Yellow"]

for i in List01:
    for j in List02:
        for k in List03:
            if i == j == k:
                print("Matched: ", i, j, k)
```

Output:
```python
Matched:  Yellow Yellow Yellow
```

---

## Learning Objectives

This notebook helps learners understand:
- How `for` loops iterate over sequences
- How nested loops work
- How to compare values inside loops
- How conditions can be used within loops

## Technologies Used
- Python 3
- Jupyter Notebook

## Purpose
This is a beginner-friendly practice notebook designed to strengthen foundational Python loop concepts.

## Author
Python Practice - Ethan Tech
