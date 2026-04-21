# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
Add code here
# Program to count lines not starting with 'T'
def count_lines_not_starting_with_T(filename):
    count = 0
    try:
        with open(filename, 'r') as file:
            for line in file:
                # Strip leading spaces and check first character
                if not line.lstrip().startswith('T'):
                    count += 1
        print("Number of lines not starting with 'T':", count)
    except FileNotFoundError:
        print("Error: File", filename, "not found.")

# Driver code
count_lines_not_starting_with_T("story.txt")


## Output
<img width="1063" height="674" alt="image" src="https://github.com/user-attachments/assets/410512ac-0cea-4344-947c-29f2a2d00d6c" />


## Result
