# The __str__() Function:
The __str__() function controls what should be returned when the class object is represented as a string.

If the __str__() function is not set, the string representation of the object is returned:

**Example:**
* The string representation of an object WITH the __str__() function:
```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

  def __str__(self):
    return f"{self.name}({self.age})"

p1 = Person("John", 36)

print(p1)
```
 The __str__() function is useful because it gives a readable, consistent way to display an object. Instead of showing something like <Person object at 0x...>, it lets you define a clean, custom output (e.g., "Alice, 30 years old").

This makes debugging and printing objects easier and keeps your code simpler by allowing print(obj) to work right out of the box.