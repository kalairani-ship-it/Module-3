# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

numbers = [10, 20, 30, 40, 50]

total = sum(numbers)

print("Sum of list elements:", total)

## Output
<img width="412" height="224" alt="Screenshot 2026-03-25 204043" src="https://github.com/user-attachments/assets/9483fb83-fa7d-401e-b567-e2f18e10b03f" />

## Result
Thus, the code was successfuly executed.

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print(l1)
## Output
<img width="391" height="229" alt="Screenshot 2026-03-25 204216" src="https://github.com/user-attachments/assets/c92e7349-215f-43b1-996f-dadd9590ebf2" />

## Result
Thus, the code was implemented successfully.


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
def remove(s):
    n = int(input("Enter index to remove: "))
    a = ""
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a

text = input("Enter a string: ")
print(remove(text))

## Output
<img width="349" height="274" alt="Screenshot 2026-03-25 204430" src="https://github.com/user-attachments/assets/eb999cd0-f61f-4088-a324-e13de883f260" />

## Result
Thus, the code was successfully implemented.


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
s = "google"
rev = s[::-1]

if s == rev:
    print("Palindrome")
else:
    print("Not Palindrome")
## Output
<img width="387" height="214" alt="Screenshot 2026-03-25 204614" src="https://github.com/user-attachments/assets/769e38a8-c9df-4251-95f3-7a438d6e7955" />

## Result
Thus, the code was successfully executed.


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
x = ('a', 'n', 5, 8, 'python')

print('n' in x)
print(8 in x)

## Output
<img width="397" height="242" alt="Screenshot 2026-03-25 204737" src="https://github.com/user-attachments/assets/a809d39d-e140-4841-82ae-9447fc8a7d60" />

## Result
Thus, the code was implemented successfully.
