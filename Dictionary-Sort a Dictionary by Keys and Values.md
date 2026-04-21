# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
Add Code here
# Program to sort dictionary by keys and values

def sort_dict(d):
    # Sort by keys
    keys_sorted = dict(sorted(d.items()))
    
    # Sort by values
    values_sorted = dict(sorted(d.items(), key=lambda item: item[1]))
    
    print("Original Dictionary:", d)
    print("Dictionary sorted by keys:", keys_sorted)
    print("Dictionary sorted by values:", values_sorted)

# Driver code
my_dict = {'banana': 'yellow', 'apple': 'red', 'cherry': 'pink', 'grape': 'green'}
sort_dict(my_dict)

## Sample Output
<img width="1050" height="675" alt="image" src="https://github.com/user-attachments/assets/d7257f74-a239-4c11-bfe8-4052d353f711" />

## Result

