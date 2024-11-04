# polymorphism:
The word "polymorphism" means "many forms", and in programming it refers to methods/functions/operators with the same name that can be executed on many objects or classes.

## Class Polymorphism
Polymorphism in Python allows methods in different classes to have the same name but behave differently based on the class they belong to. This lets you use the same method name to perform various actions based on the object’s class.

Example
Here's a simple example with two classes, Dog and Cat, each with their own sound method:

```python

class Dog:
    def sound(self):
        return "Woof!"

class Cat:
    def sound(self):
        return "Meow!"

# Using polymorphism
def make_sound(animal):
    print(animal.sound())

dog = Dog()
cat = Cat()

make_sound(dog)  # Output: Woof!
make_sound(cat)  # Output: Meow!
```