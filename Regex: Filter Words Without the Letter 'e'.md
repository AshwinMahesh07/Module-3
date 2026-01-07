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
<img width="662" height="196" alt="image" src="https://github.com/user-attachments/assets/7d81d556-bac4-4542-abcd-618677eedc51" />
## Output
<img width="187" height="49" alt="image" src="https://github.com/user-attachments/assets/8b5649c1-17e7-4ce3-a76a-f9dab7dfaabc" />

## Result
<img width="347" height="50" alt="image" src="https://github.com/user-attachments/assets/098b7f02-27e6-43d2-986c-f20d85855a9e" />
