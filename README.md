# 🔀 Sorting Heterogeneous Data Using Python

Welcome to my project where I tackle the challenge of **sorting heterogeneous data** — data that includes mixed types such as integers, floats, strings, booleans, and more — using pure Python.

This project demonstrates **robust Python logic** for handling, validating, and sorting datasets that are not uniform, a scenario common in real-world data processing.

---

## 📌 What This Project Covers

- ✅ Handling mixed data types (int, float, str, bool, None, etc.)
- ✅ Sorting based on rules like type priority or value
- ✅ Custom sorting functions using `lambda`, `key`, and `sorted()`
- ✅ Edge case handling — `None`, empty strings, special characters
- ✅ Examples with nested lists and dictionaries

---

## 📂 Folder Structure

```bash
project-to-sort-heterogenous-data-by-python/
├── main_sorting_logic.py         # Main Python script for sorting logic
├── test_cases.py                 # Example test inputs and outputs
├── sorting_rules.md              # Explanation of sorting logic used
├── example_outputs.txt           # Sample outputs of the program
└── README.md
```

---

## 🧠 Key Concepts Used

- `isinstance()` for type detection
- `sorted()` with custom `key` functions
- Type ranking logic for order like: int < float < bool < str < None

---

## 🚀 Sample Logic Used

```python
def sort_heterogeneous(data):
    type_priority = {int: 0, float: 1, bool: 2, str: 3, type(None): 4}
    return sorted(data, key=lambda x: (type_priority.get(type(x), 5), x))
```

---

## 🔗 Connect With Me

- 💻 GitHub → [Click Here](https://github.com/akshat09105)
- 💼 LinkedIn → [Click Here](https://www.linkedin.com/in/akshat-gupta-6a27a331a/)
- 🧠 Kaggle → [Click Here](https://www.kaggle.com/akshat9105)

---

## 🙌 Final Thoughts

This project was a fun way to improve my **Python problem-solving skills**, especially around edge-case handling and type-based sorting logic.

> “The power of Python lies in how flexibly it handles the real world — not just the clean data.”

**Happy Learning!**  
— *Akshat Gupta*
