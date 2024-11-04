# Iterators in python:
An iterator is an object that contains a countable number of values.

An iterator is an object that can be iterated upon, meaning that you can traverse through all the values.

Technically, in Python, an iterator is an object which implements the iterator protocol, which consist of the methods `__iter__()` and `__next__()`.

```python
# An iterable: a list
my_list = [1, 2, 3]

# Getting an iterator from the iterable
my_iterator = iter(my_list)

# Using the iterator to get items one by one
print(next(my_iterator))  # Output: 1
print(next(my_iterator))  # Output: 2
print(next(my_iterator))  # Output: 3
```

