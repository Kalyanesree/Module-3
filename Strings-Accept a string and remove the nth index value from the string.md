# EX 3 (C) Strings-Remove Nth Index Character from a String

## Aim
To write a Python program that accepts a string and removes the character at a specified index.

## Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## Program
```
n = int(input())
a = input()

def remove_char(a, n):
    result = ""
    for i in range(len(a)):
        if i != n:
            result += a[i]
    return result

print(remove_char(a, n))
```

## Output
<img width="1190" height="302" alt="image" src="https://github.com/user-attachments/assets/2f2801ed-353f-41f1-b5a7-15efcde40b4d" />

## Result
 Thus, the  Python program that accepts a string and removes the character at a specified index is executed successfully.
