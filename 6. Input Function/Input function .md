# 🐍 Input Function in Python

---

## 📌 Introduction

The `input()` function is used to **take input from the user**.  
By default, it returns the input in the form of a **string**.

---

## 🧠 Syntax

```python
input(prompt)
```

- `prompt` → (optional) A message displayed before taking input

---

## 💡 Explanation

- The prompt is shown on the screen  
- The program waits for the user to enter something  
- After pressing **Enter**, the input is stored as a string  

---

## 📝 Example

```python
input("What is your name? ")
```

### ▶️ Output

```
What is your name? Jenny
```

👉 The text is displayed and the cursor waits for user input.  
👉 After entering the name and pressing Enter, the program continues.

---

## ⚙️ How Execution Works

- The line:
```python
input("What is your name?")
```

- Gets replaced internally with the value entered by the user  

Example:
```
Jenny
```

⚠️ Note:  
This replacement happens **behind the scenes** and is not visible on the screen. :contentReference[oaicite:0]{index=0}

---

## 🔗 Combining `input()` with `print()`

```python
print("Hello " + input("What is your name? "))
```

### ▶️ Output

```
What is your name? Jenny
Hello Jenny
```

---

## 🧪 Coding Exercise

### 🎯 Problem

Take the user's name as input and display:

```
Hey [name], How are you?
```

---

### ✅ Solution

```python
print("Hey " + input("What is your name? ") + ", How are you?")
```

---

## 🚀 Key Points

- `input()` always returns a **string**
- Prompt is optional
- Used for **user interaction**
- Can be combined with `print()` and concatenation

---

⭐ *Practice taking different inputs to improve your understanding!*