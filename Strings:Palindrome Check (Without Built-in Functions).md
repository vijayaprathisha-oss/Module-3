# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```def palindrome(s):
    a=s[::-1]
    if s==a:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
s=input()
palindrome(s)
```

## Output
<img width="1029" height="864" alt="image" src="https://github.com/user-attachments/assets/0b4e7673-0a87-4a9b-840d-05b783fdf92e" />


## Result
Thus,the given python program has been executed successfully.
