# 🐍 String Manipulation in Python

---

## 📌 Introduction

String manipulation refers to **modifying, analyzing, and working with text data** in Python.  
Strings are one of the most commonly used data types.

---

## 🧠 What is a String?

A string is a sequence of characters enclosed in quotes.

```python
name = "Python"
```

---

## ⚡ Common String Operations

---

## 🔗 1. Concatenation

Joining two or more strings using `+`.

```python
first = "Hello"
second = "World"

print(first + " " + second)
```

---

## 🔁 2. Repetition

Repeat a string using `*`.

```python
print("Hi " * 3)
```

---

## 🔍 3. Indexing

Access characters using index numbers.

```python
text = "Python"

print(text[0])   # P
print(text[-1])  # n
```

---

## ✂️ 4. Slicing

Extract a part of a string.

```python
text = "Python"

print(text[0:3])  # Pyt
print(text[2:])   # thon
```

---

## 🔠 5. Changing Case

```python
text = "python"

print(text.upper())   # PYTHON
print(text.lower())   # python
print(text.title())   # Python
```

---

## 🔄 6. Replacing Text

```python
text = "Hello World"

print(text.replace("World", "Python"))
```

---

## 📏 7. String Length

```python
text = "Python"

print(len(text))
```

---

## 🔎 8. Checking Content

```python
text = "python123"

print(text.isalpha())  # False
print(text.isdigit())  # False
print(text.isalnum())  # True
```

---

## ✨ 9. Stripping Spaces

```python
text = "  Python  "

print(text.strip())
```

---

## 🔗 10. Splitting and Joining

```python
text = "Python is fun"

print(text.split())  

words = ["Python", "is", "fun"]
print(" ".join(words))
```

---

## ⚠️ Important Notes

- Strings are **immutable** (cannot be changed directly)
- Indexing starts from **0**
- Negative indexing starts from **-1**

---

## 🧪 Practice Examples

```python
text = "hello python"

print(text.upper())
print(text.replace("python", "world"))
print(text[0:5])
```

---

## 🚀 Conclusion

String manipulation is essential for:
- Text processing  
- Data cleaning  
- User input handling  

Mastering strings will make your Python skills much stronger.

---

⭐ *Practice different string operations to become confident!*
