# 🎯 Number Guessing Game

A simple and interactive web-based Number Guessing Game built using **HTML**, **CSS**, **JavaScript**, and **jQuery**.

This game generates a random number between **1 and 100**, and the player must guess the number with the help of hints like *Too High* or *Too Low*.

---

## 🚀 Features

- Random number generation between 1–100
- User input validation
- Hint messages (Too High / Too Low)
- Tracks:
  - Number of Attempts
  - Best Score
  - Total Games Played
- Guess History Display
- Secret number stored using **Session Storage**
- Statistics stored using **Session Storage**
- Secret number persists on page refresh
- New Game option
- Clear Stats option (removes all stored data)

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript
- jQuery
- Browser Session Storage API

---

## 🎮 How to Play

1. Enter a number between **1 and 100** in the input field.
2. Click on **Submit Guess**.
3. The game will give hints:
   - 📉 Too Low → Guess a higher number.
   - 📈 Too High → Guess a lower number.
4. Continue guessing until you find the correct number.
5. The game tracks your:
   - Attempts
   - Best Score
   - Total Games Played

---

## 🔄 Buttons Description

| Button | Function |
|--------|----------|
| Submit Guess | Checks the entered number |
| New Game | Starts a new game with a new secret number |
| Clear Stats | Clears all stored data and resets the game |

---

## 💾 Storage Used

This project uses **Session Storage** to store:

- Secret Number
- Best Score
- Games Played

> Session Storage keeps the data even if the page is refreshed but clears it when the browser tab is closed.

---

## 🧠 Project Workflow

1. Game generates a random number.
2. User enters a guess.
3. Input is validated.
4. Guess is compared with secret number.
5. Hint message is shown.
6. Attempts and history are updated.
7. Game ends when correct number is guessed.
8. Stats are saved in session storage.

---

## 📂 Project Structure

