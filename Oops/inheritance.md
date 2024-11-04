```python
class Person:
    def __init__(self, name, id):
        self.name = name
        self.id = id

    def greet(self):
        print(f"Hi dear {self.name}, your id no is {self.id}")

    def __str__(self):
        return f"Person(Name: {self.name}, ID: {self.id})"


# Creating a subclass that inherits from Person
class Student(Person):
    def __init__(self, name, id, grade_level):
        # Initialize attributes from the parent class using super()
        super().__init__(name, id)
        self.grade_level = grade_level  # Additional attribute for Student

    # Additional method specific to Student
    def show_student_details(self):
        print(f"Student Name: {self.name}, ID: {self.id}, Grade Level: {self.grade_level}")

    def __str__(self):
        return f"Student(Name: {self.name}, ID: {self.id}, Grade Level: {self.grade_level})"


# Create an instance of Person
p1 = Person("John", 36)
p1.greet()
print(p1)

# Create an instance of Student
s1 = Student("Alice", 42, "10th Grade")
s1.greet()  # Inherited from Person
s1.show_student_details()  # Specific to Student
print(s1)
```