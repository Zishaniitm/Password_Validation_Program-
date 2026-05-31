# Python Mini Projects 🐍
# Password Validation Program Using Python

A collection of beginner Python programs built to practise core concepts — regex, functions, loops, and user input handling.

---

## Projects

### 1. Password Validation Program

A password strength checker that scores a password out of **100** based on multiple security rules.

**How scoring works:**

| Rule | Points |
|---|---|
| Length >= 10 characters | +20 |
| Contains uppercase letter | +10 |
| Contains lowercase letter | +10 |
| Contains a digit | +10 |
| Contains at least 1 special character | +10 |
| No repeating characters (3+ in a row) | +10 |
| Username not found inside password | +10 |
| Contains 2+ different special characters | +20 |
| **Maximum score** | **100** |

**Strength levels:**

- 80–100 → Strong
- 50–79 → Moderate
- Below 50 → Weak

**Concepts used:** `re` module, regex patterns, functions, string methods

---

### 2. Guess The Number

A classic number guessing game where the program picks a random number and the user tries to guess it within a limited number of attempts.

**How it works:**
- Program generates a random number in a given range
- Player enters guesses one at a time
- After each guess, a hint is shown: too high, too low, or correct
- Game ends when the player guesses correctly or runs out of attempts

**Concepts used:** `random` module, loops, conditionals, user input

---

## How to Run

**Option 1 — Google Colab (no setup needed)**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Zishaniitm/GuessTheNumber.java/blob/main/passAndUserValidator.ipynb)

**Option 2 — Run locally**

```bash
# Clone the repo
git clone https://github.com/Zishaniitm/GuessTheNumber.java.git
cd GuessTheNumber.java

# Run the notebook
jupyter notebook passAndUserValidator.ipynb
```

**Requirements:** Python 3.x · `re` (built-in) · `random` (built-in) — no external libraries needed.

---

## Author

**Zishan** — IIT Madras  
[GitHub](https://github.com/Zishaniitm)
