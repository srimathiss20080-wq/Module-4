## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 1, 'b': 2, 'c': 3} 
dict2 = {'b': 20, 'd': 4}

def merge(): 
    merged = {**dict1, **dict2} 
    print(merged)

merge()
```

## Output

<img width="1387" height="427" alt="image" src="https://github.com/user-attachments/assets/b86eb5d4-f14a-49d6-a1a2-968b2a818f5e" />

## Result
Thus To write a Python program that merges two dictionaries and combines their key-value pairs. Hence the code has been executed successfully.

