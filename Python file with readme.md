# Python Strings and Tuples 

## Overview
This project covers basic Python string operations and tuple manipulation:
concatenation, indexing, slicing, built-in string methods, and tuple operations.

## Files
- `assignment_strings_tuples.ipynb` – Google Colab with the solution
- `assignment_strings_tuples.py` – the same solution as a Python script
- `README.md` – this file

## How to Run
**Google Colab**
1. Open the notebook in Google Colab.
2. Click **Runtime → Run all**.
3. When prompted, enter your name (e.g. `Karthik`).

**Python script**
```
python assignment_strings_tuples.py
```

## What the Program Does

### 1. String Concatenation
- Takes the user's name with `input()` and joins it with `"Hello"` → `Hello Karthik`
- Adds `", welcome to Python programming"` → `Hello Karthik, welcome to Python programming`

### 2. String Slicing and Indexing
Using the concatenated string:
- First character, last character
- First 5 characters, last 11 characters
- Reversed string (`[::-1]`)
- The word "Python" extracted by slicing

### 3. String Methods
Using `strM = "Python beginner tutorial"`:
- `upper()`, `lower()`, `capitalize()`
- `count("t")`
- `replace("Python", "Data Analytics")`

### 4. Tuples
Using `(10, 20, 30)` and `(40, 50, 60)`:
- Concatenation into `t_combine`
- Repetition (3 times)
- Accessing the 3rd element, first three elements, and last three elements
- Immutability demo: assigning to a tuple item raises a `TypeError`

## Sample Output
```
Enter your Name: karthik
Hello karthik
Hello karthik, welcome to Python programming
...
a. t_combine            : (10, 20, 30, 40, 50, 60)
c. 3rd element          : 30
Immutability demo       : 'tuple' object does not support item assignment
```

## Skills Demonstrated
String concatenation, user input handling, indexing and slicing, string methods,
tuple creation, concatenation, repetition, indexing and slicing, and immutability.

## Link : ## https://colab.research.google.com/drive/19KaUYx-im0bO3CX8_Y12bhDuvAJu4xXF#scrollTo=CBsWdyHhY-Lu
## Author
Karthik.M
