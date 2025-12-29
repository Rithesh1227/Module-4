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
```
with open('story.txt', 'r') as file:
    count = 0 
    for line in file:
        if not line.lstrip().startswith('T'):
            count += 1  
print("Number of lines not starting with 'T':", count)
```
## Output
<img width="1549" height="180" alt="image" src="https://github.com/user-attachments/assets/cc343f5c-ea3f-4420-964e-40bf22de36b7" />

## Result
