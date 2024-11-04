# Encapsulation in Python (with Example)
Encapsulation in Python is an OOP concept that restricts access to certain parts of an object to protect its data. This is done by defining attributes and methods as public, protected, or private.

Public Attributes/Methods: Accessible from outside the class.
Protected Attributes/Methods: Indicated by a single underscore _attribute, meant to be used only within the class or its subclasses.
Private Attributes/Methods: Indicated by a double underscore __attribute, meant to be accessed only within the class itself.

```python
class Person:
    def __init__(self, name, age):
        self.name = name            # Public attribute
        self._age = age             # Protected attribute
        self.__social_security = "123-45-6789"  # Private attribute

    def display_info(self):
        print(f"Name: {self.name}, Age: {self._age}")

    def __display_ssn(self):  # Private method
        print(f"SSN: {self.__social_security}")

# Creating an instance of Person
person = Person("Alice", 30)

# Accessing public attribute
print(person.name)  # Output: Alice

# Accessing protected attribute (discouraged but possible)
print(person._age)  # Output: 30

# Trying to access private attribute directly (will raise an AttributeError)
# print(person.__social_security)  # Error

# Instead, access private attributes/methods through a public method
person.display_info()  # Output: Name: Alice, Age: 30

```
