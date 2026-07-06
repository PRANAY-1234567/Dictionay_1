🔡 Count Frequency of Characters in a String (Python)

📌 Description

This program counts how many times each character appears in a given string.
It uses a dictionary to store characters as keys and their frequencies as values.

🧩 Problem Statement

Given a word:

"apple"

Count the occurrence of each character.

✅ Code
word = "apple"
count = {}

for ch in word:
    count[ch] = count.get(ch, 0) + 1

print(count)

🧠 Explanation

An empty dictionary count is created
The loop goes through each character in the string
get(ch, 0) returns the current count (0 if the key does not exist)
The count is increased by 1 for each occurrence
The final dictionary shows character frequencies

🖨 Example Output
{'a': 1, 'p': 2, 'l': 1, 'e': 1}

🛠 Concepts Used

Strings

Dictionaries

Loops

get() method

🎯 Use Cases

String analysis

Interview preparation

Beginner Python practice

Text processing

🚀 Possible Improvements

Ignore case sensitivity
Handle sentences with spaces
Convert into a function
Use collections.Counter

👨‍💻 Author

Pranay Jadhao

<img width="635" height="625" alt="image" src="https://github.com/user-attachments/assets/d1d66723-3640-4d90-a788-abdabb464b02" />
