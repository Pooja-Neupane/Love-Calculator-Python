# 💖 Love Calculator - A Fun Python Project 💖

A simple and fun Python program that calculates a love compatibility score between two names. This project is great for beginners to practice Python basics like string manipulation, functions, and user input.

---

## 📌 Features

- Takes two names as input
- Counts the frequency of letters in the words **TRUE** and **LOVE**
- Generates a “Love Score” based on string logic
- Displays custom messages based on compatibility percentage
- Easy to understand and customize!

---

## 🧠 How It Works

The logic is based on counting the number of times letters in the words "TRUE" and "LOVE" appear in the combined names.

```python
true_count = sum(combined_names.count(letter) for letter in "true")
love_count = sum(combined_names.count(letter) for letter in "love")
love_score = int(str(true_count) + str(love_count))
