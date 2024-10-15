
# Python String Methods

## 1. `str.lower()`
**Use Case:** Convert all characters in a string to lowercase.

```python **\'**
   - **Use Case:** Insert a single quote in a string that is enclosed in single quotes.
   ```python
   text = 'It\'s a beautiful day!'
   
   print(text)  # Output: It's a beautiful day!
text = "Hello, World!"
print(text.lower())  # Output: "hello, world!"
```

## 2. `str.upper()`
**Use Case:** Convert all characters in a string to uppercase.

```python
text = "Hello, World!"
print(text.upper())  # Output: "HELLO, WORLD!"
```

## 3. `str.title()`
**Use Case:** Convert the first character of each word to uppercase.

```python
text = "hello, world!"
print(text.title())  # Output: "Hello, World!"
```

## 4. `str.strip()`
**Use Case:** Remove leading and trailing whitespace from a string.

```python
text = "   Hello, World!   "
print(text.strip())  # Output: "Hello, World!"
```

## 5. `str.replace(old, new)`
**Use Case:** Replace occurrences of a substring with another substring.

```python
text = "Hello, World!"
print(text.replace("World", "Python"))  # Output: "Hello, Python!"
```

## 6. `str.split(sep)`
**Use Case:** Split a string into a list of substrings based on a delimiter.

```python
text = "Hello, World!"
print(text.split(", "))  # Output: ['Hello', 'World!']
```

## 7. `str.join(iterable)`
**Use Case:** Join elements of an iterable (like a list) into a single string with a specified separator.

```python
words = ['Hello', 'World']
print(", ".join(words))  # Output: "Hello, World"
```

## 8. `str.find(sub)`
**Use Case:** Find the first occurrence of a substring and return its index, or -1 if not found.

```python
text = "Hello, World!"
print(text.find("World"))  # Output: 7
```

## 9. `str.count(sub)`
**Use Case:** Count the number of occurrences of a substring in a string.

```python
text = "Hello, World! Hello!"
print(text.count("Hello"))  # Output: 2
```

## 10. `str.startswith(prefix)`
**Use Case:** Check if a string starts with a specified prefix.

```python
text = "Hello, World!"
print(text.startswith("Hello"))  # Output: True
```

## 11. `str.endswith(suffix)`
**Use Case:** Check if a string ends with a specified suffix.

```python
text = "Hello, World!"
print(text.endswith("World!"))  # Output: True
```

## 12. `str.isdigit()`
**Use Case:** Check if all characters in a string are digits.

```python
text = "12345"
print(text.isdigit())  # Output: True
```

## 13. `str.isalpha()`
**Use Case:** Check if all characters in a string are alphabetic.

```python
text = "Hello"
print(text.isalpha())  # Output: True
```

## 14. `str.isalnum()`
**Use Case:** Check if all characters in a string are alphanumeric (letters and digits).

```python
text = "Hello123"
print(text.isalnum())  # Output: True
```

## 15. `str.capitalize()`
**Use Case:** Capitalize the first character of the string.

```python
text = "hello, world!"
print(text.capitalize())  # Output: "Hello, world!"
```

## 16. `str.splitlines()`
**Use Case:** Split a string into a list where each line is a list item.

```python
text = "Hello\nWorld!"
print(text.splitlines())  # Output: ['Hello', 'World!']
```

## 17. `str.swapcase()`
**Use Case:** Swap the case of all characters in a string.

```python
text = "Hello, World!"
print(text.swapcase())  # Output: "hELLO, wORLD!"
```

## 18. `str.zfill(width)`
**Use Case:** Pad a numeric string with zeros on the left, to fill a specified width.

```python
text = "42"
print(text.zfill(5))  # Output: "00042"
```

