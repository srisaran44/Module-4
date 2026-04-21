## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

Add code here
# Program to merge two dictionaries
def merge_dicts(dict1, dict2):
    # Using dictionary unpacking
    merged = {**dict1, **dict2}
    return merged

# Driver code
dict_a = {'a': 1, 'b': 2, 'c': 3}
dict_b = {'d': 4, 'e': 5, 'b': 10}  # Note: 'b' key overlaps

print("Dictionary 1:", dict_a)
print("Dictionary 2:", dict_b)

result = merge_dicts(dict_a, dict_b)
print("Merged Dictionary:", result)


## Output
<img width="937" height="672" alt="image" src="https://github.com/user-attachments/assets/cca6cbad-8bbb-4437-9363-f408bb3eea35" />


## Result
