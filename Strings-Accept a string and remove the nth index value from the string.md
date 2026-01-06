# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
s = input()
def remove(s):
    s1 = ""
    vowels = "aeiouAEIOU"
    for i in s:
        if i in vowels:
            s1+=i
    print(s1)
```

## Output

<img width="906" height="385" alt="image" src="https://github.com/user-attachments/assets/6a3b2caa-c7cc-424c-85a5-eafb22fb1a56" />

## Result
Thus,the program has been executed successfully.
