# 🐍 Python Programming Practice Repository

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Practice](https://img.shields.io/badge/Practice-Topic--wise-green.svg)
![Beginner Friendly](https://img.shields.io/badge/Level-Beginner-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-orange.svg)

A comprehensive collection of Python programs organized by topic. Perfect for learning Python fundamentals and practicing core concepts!

## 📚 Topics Covered

### 📋 Lists (`LISTS/`)
Practice working with Python lists - one of the most versatile data structures.

| Program | Description |
|---------|-------------|
| `Largest_number.py` | Find the largest number in a list |
| `Smallest_Number` | Find the smallest number in a list |
| `sum_of_elements_in_list` | Calculate sum of all list elements |
| `even_numbers_from_list` | Extract even numbers |
| `odd_numbers_in_list` | Extract odd numbers |
| `reversing_list` | Reverse a list |
| `count_occurances` | Count element occurrences |
| `counting_each_element` | Count all unique elements |
| `duplicate_elements_removing` | Remove duplicates from list |
| `merging_two_list` | Merge two lists |
| `mering_without_duplicates_in_ascending` | Merge lists without duplicates |
| `converting_list_to_string` | Convert list to string |
| `separating_alphabets_numbers` | Separate letters and numbers |
| `second_largest_number` | Find second largest element |

### 🔢 Operators (`Operators/`)
Learn about different types of operators in Python.

| Program | Description |
|---------|-------------|
| `Arithematic_operators.py` | +, -, *, /, //, %, ** |
| `Asignment_operators.py` | =, +=, -=, *=, /= |
| `Comparision_Operators.py` | ==, !=, <, >, <=, >= |
| `Logical_Operators.py` | and, or, not |
| `Identity_operators.py` | is, is not |
| `Membership_operators.py` | in, not in |

### 📦 Sets (`SETS/`)
Practice with sets - unordered collections of unique elements.

| Program | Description |
|---------|-------------|
| `unique_elements` | Extract unique elements |
| `Common_elements` | Find common elements between sets |
| `set_difference` | Find set difference |

### 📝 Tuples (`TUPLES/`)
Learn about tuples - immutable ordered collections.

| Program | Description |
|---------|-------------|
| `Sum_of_elements` | Calculate sum of tuple elements |
| `max_element` | Find maximum element |
| `sorting_elements` | Sort tuple elements |
| `count_occurances` | Count occurrences in tuple |

## 🚀 Quick Start

### Running a Program

1. **Navigate to the topic folder**
   ```bash
   cd LISTS
   ```

2. **Run a specific program**
   ```bash
   python Largest_number.py
   ```

3. **Or run all programs in a folder**
   ```bash
   # For example, run all list programs
   for file in *.py; do python "$file"; done
   ```

### Prerequisites
- Python 3.6 or higher
- A text editor or IDE (VS Code, PyCharm, etc.)

## 📁 Project Structure

```
PYTHON/
├── LISTS/              # List operations
│   ├── Largest_number.py
│   ├── Smallest_Number
│   ├── sum_of_elements_in_list
│   └── ... (14 programs)
├── Operators/          # Python operators
│   ├── Arithematic_operators.py
│   ├── Comparision_Operators.py
│   ├── Logical_Operators.py
│   └── ... (6 programs + practice questions)
├── SETS/              # Set operations
│   ├── unique_elements
│   ├── Common_elements
│   └── set_difference
├── TUPLES/            # Tuple operations
│   ├── Sum_of_elements
│   ├── max_element
│   ├── sorting_elements
│   └── count_occurances
└── README.md          # This file
```

## 💡 Learning Path

### For Beginners
1. Start with **Operators** to understand Python's building blocks
2. Move to **Lists** as they're the most commonly used data structure
3. Progress to **Sets** and **Tuples** for advanced data handling

### Recommended Order
```
Operators → Lists → Sets → Tuples
```

## 🎯 Practice Tips

1. **Read the code** - Understand what each line does
2. **Modify and experiment** - Try changing values and see results
3. **Solve without looking** - Attempt to write similar programs
4. **Add comments** - Document your understanding
5. **Create variations** - Extend the programs with new features

## 🔧 Python Concepts Practiced

- ✅ Variables and Data Types
- ✅ Operators and Expressions
- ✅ Control Flow (if-else)
- ✅ Loops (for, while)
- ✅ List/Set/Tuple Methods
- ✅ Functions
- ✅ String Manipulation
- ✅ File Handling Basics

## 📖 Example Programs

### Largest Number in List
```python
# Largest_number.py
numbers = [3, 7, 2, 9, 4, 1, 8]
largest = max(numbers)
print(f"The largest number is: {largest}")
```

### List with Duplicates Removed
```python
# duplicate_elements_removing
my_list = [1, 2, 2, 3, 4, 4, 5]
unique_list = list(set(my_list))
print(unique_list)  # [1, 2, 3, 4, 5]
```

## 🤝 Contributing

Found a bug or want to add more programs? Contributions are welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-program`)
3. Add your program with clear naming
4. Commit changes (`git commit -m 'Add new program'`)
5. Push to the branch (`git push origin feature/new-program`)
6. Open a Pull Request

## 📝 Program Naming Conventions

- Use snake_case for file names
- Be descriptive about functionality
- Include the operation type in the name

## ✅ Checklist for New Programs

- [ ] Clear, descriptive filename
- [ ] Well-commented code
- [ ] Works correctly
- [ ] Handles edge cases
- [ ] Has docstring or header comment

## 🏆 Progress Tracking

| Topic | Programs | Status |
|-------|----------|--------|
| Lists | 14 | ✅ |
| Operators | 6 | ✅ |
| Sets | 3 | ✅ |
| Tuples | 4 | ✅ |

**Total Programs: 27+**

## 📚 Resources

- [Python Official Documentation](https://docs.python.org/3/)
- [Python Practice Exercises](https://www.w3resource.com/python-exercises/)
- [Real Python Tutorials](https://realpython.com/)

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Built with ❤️ by [Chigurla Aparna](https://github.com/ChigurlaAparna)

---

<div align="center">

🐍 **Happy Coding!** 🐍

*Practice makes perfect*

</div>
