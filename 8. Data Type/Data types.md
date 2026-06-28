# Python Data Types


## What are Data Types?

- A data type tells the type of value/data stored in a variable.
- In Python, data types are implemented as classes, and variables are objects (instances) of these classes.
- Python automatically determines the type of a variable; you do not need to declare it explicitly.

```python
var1 = 10         # int
var2 = 9.4        # float
var3 = "shubham"  # str
```

## Common Python Data Types

- `int`
- `float`
- `complex`
- `str`
- `list`
- `tuple`
- `range`
- `dict`
- `bool`
- `set`

---

# 1. Integer (`int`)

Integers represent whole numbers (positive or negative).

```python
a = 123
print(a)
```

Python integers have no fixed size limit (limited only by available memory).

```python
a = 901234567890123456789
print(a)
```

### Number Prefixes

| Prefix       | Number System | Example  |
|--------------|---------------|----------|
| `0b` or `0B` | Binary        | `0b11`   |
| `0o` or `0O` | Octal         | `0o11`   |
| `0x` or `0X` | Hexadecimal   | `0x11`   |

```python
print(0b11)   # 3
print(0o11)   # 9
print(0x11)   # 17
```

### Checking the Type

```python
var = 4
print(type(var))
# <class 'int'>
```

---

# 2. Float (`float`)

Floats represent decimal numbers.

```python
x = 4.2
y = 4.0
z = 0.2
```

---

# 3. String (`str`)

A string is a sequence of characters.

```python
name = "shubham"
```

### Accessing Characters

```python
print("shubham"[0])  # s
print("shubham"[3])  # b
```

```python
name = "shubham"
print(name[5])
print(len(name))
```

### Using Quotes Inside Strings

```python
name = "shubham's lectures \"CS/IT\""
print(name)
```

Use a backslash (`\`) to escape special characters.

### String Operations

```python
print(5 * "shubham")
```

```python
print("100" + "100")  # 100100
print(100 + 100)      # 200
```

---

# 4. Boolean (`bool`)

Boolean values have only two possible values:

- `True`
- `False`

> `True` and `False` are case-sensitive and must start with capital letters.

```python
val = True
print(val)
print(type(val))
# <class 'bool'>
```

```python
a = 1
b = 2

val = a < b
print(val)        # True
print(type(val))  # <class 'bool'>
```

---

# Summary

| Data Type | Description                  | Example         |
|-----------|------------------------------|-----------------|
| `int`     | Whole numbers                | `10`            |
| `float`   | Decimal numbers              | `9.4`           |
| `str`     | Sequence of characters       | `"shubham"`     |
| `bool`    | Logical values               | `True`, `False` |
| `list`    | Ordered mutable collection   | `[1, 2, 3]`     |
| `tuple`   | Ordered immutable collection | `(1, 2, 3)`     |
| `dict`    | Key-value pairs              | `{"a": 1}`      |
| `set`     | Unordered unique values      | `{1, 2, 3}`     |

