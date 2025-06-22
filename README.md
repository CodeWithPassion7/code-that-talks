# 🗣️ Code That Talks

This is a simple Python project that makes your code talk using the `pyttsx3` text-to-speech library.  
Perfect for beginners who want to explore speech features in Python — no internet required!

---

## 📌 What It Does

- Converts text to speech
- Uses the `pyttsx3` offline speech engine
- Shows how to use `say()` and `runAndWait()` in Python

---

## 🧪 Example Code

```python
import pyttsx3

engine = pyttsx3.init()
engine.say("Hello Sumit!")
engine.runAndWait()
