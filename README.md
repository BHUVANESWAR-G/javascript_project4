
---

# 🎯 Guess the Number Game

A simple and interactive number guessing game built using **HTML** and **JavaScript**. The player has to guess a randomly generated number between **1 and 10**.

---

## 📌 Project Overview

This is a beginner-friendly web project where:

* A random number is generated between 1–10
* The user inputs a number
* The system checks whether the guess is correct or not
* The score decreases for every wrong attempt

---

## 🚀 Features

* 🔢 Random number generation (1–10)
* 🎯 User input validation
* 📉 Score tracking system
* ❌ Wrong guess feedback
* 🎉 Winning alert message

---

## 🛠️ Technologies Used

* HTML5
* JavaScript (Vanilla JS)

---

## 📂 Project Structure

```
Guess-The-Number/
│── index.html   # Main game file
```

---

## ▶️ How to Run the Project

1. Download or clone the repository
2. Open the `index.html` file in any web browser
3. Enter a number between 1 and 10
4. Click **Check** to see the result

---

## 🎮 How It Works

* The game generates a random number using:

  ```javascript
  Math.floor(Math.random() * 10 + 1)
  ```
* Player starts with a score of **10**
* Each wrong guess reduces the score by **1**
* Game continues until the correct number is guessed

---

## 📸 Sample Gameplay

* Input a number → Click **Check**
* If correct → 🎉 "You are Right!"
* If wrong → ❌ Score decreases

---

## 💡 Future Improvements

* Add restart/reset button
* Limit number of attempts
* Provide hints (higher/lower)
* Improve UI with CSS styling

---
