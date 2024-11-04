# Abstraction 

Abstraction hides complex details and shows only the necessary parts. In Python, this can be done using abstract classes.

```python
class Shape:
    # This is a general class for shapes. The area method is a placeholder.
    def area(self):
        raise NotImplementedError("This method should be overridden in subclasses")

class Rectangle(Shape):
    # Rectangle inherits from Shape and provides its own area calculation.
    def __init__(self, width, height):
        self.width = width       # Setting the width of the rectangle
        self.height = height     # Setting the height of the rectangle

    def area(self):
        # Calculates the area of a rectangle (width * height)
        return self.width * self.height

# Create a Rectangle instance and calculate its area
rect = Rectangle(3, 4)
print(rect.area())  # Output: 12


```