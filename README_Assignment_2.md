# Python Assignment 2: List, Dictionary, Set & Conditional Statements

A Jupyter notebook that solves the Python Fundamentals Assignment 2 on lists, dictionaries, sets and conditional statements.

## Contents

| File | Description |
|------|-------------|
| `Python_Assignment_2.ipynb` | Notebook with all solutions, one section per question |
| `README.md` | This file |

## Topics Covered

### 1. List
- **Creation:** `age_list` with five integers and `name_list` with five strings
- **Modification:** `append()`, `insert()`, `remove()`, `pop()`, `extend()` and `sort(reverse=True)`
- **Statistics:** max, min and sum of `age_list`
- **Access:** first element, last element, slicing (index 2 to 4) and reverse order

### 2. Dictionary
- Creating `student_marks` with five students and their marks (0 to 100)
- Accessing a student's mark by key
- Adding a new student, `"Janani"`, with 80 marks
- Updating an existing student's mark to 82
- Using `keys()`, `values()` and `items()`

### 3. Sets
- Creating `my_set` from a list with duplicate values and explaining the output (sets keep only unique values and are unordered)
- Showing the `TypeError` raised by `my_set[4] = 's'` (sets do not support indexing or item assignment)
- Union and intersection of `set1` and `set2`

### 4. Conditional Statements: Performance Category Program
Takes a score from 0 to 10 and prints a category with a message:

| Score | Category |
|-------|----------|
| Greater than 7 | Above Average |
| 4 to 7 (inclusive) | Average |
| Less than 4 | Below Average |
| Below 0 or above 10 | Invalid input message |

## How to Run

### Google Colab (no installation needed)
1. Go to [colab.research.google.com](https://colab.research.google.com) and sign in.
2. Click **File → Upload notebook** and select `Python_Assignment_2.ipynb`.
3. Run each cell in order with **Shift + Enter**.

### Local Jupyter
```bash
pip install notebook
jupyter notebook Python_Assignment_2.ipynb
```

## Important Notes
- Run the cells **in order**, because later cells use variables created in earlier ones.
- The last cell asks for a score. Type a number in the input box and press **Enter**.
- Run the last cell several times with different scores (for example 9, 7, 4 and 2) to see every category.
- The `TypeError` in the sets section is intentional. It is caught with `try/except` so the notebook keeps running.

## Sample Output

```
Enter your score (0 to 10): 7
Average: Good effort! Keep practicing, there's room for improvement.
```

```
Union: {1, 2, 3, 5, 7, 8, 9, 10}
Intersection: {3, 5}
```

## Requirements
- Python 3.x
- No external libraries needed

## Author
Name: Shihana
