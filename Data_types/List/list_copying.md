# Copy a List:

You cannot copy a list simply by typing list2 = list1, because: list2 will only be a reference to list1, and changes made in list1 will automatically also be made in list2.

## Use the copy method:

**Example:**
```python
thislist = ["apple", "banana", "cherry"]
mylist = thislist.copy()
print(mylist)
```
## List() method:

we can alse use the list() method to copy a list:

**Example:**
```python
thislist = ["apple", "banana", "cherry"]
mylist = list(thislist)
print(mylist)
```
## Slice Operator (:) :
you can also make the copy of a list by using the `(:)` slice operator:
**Example:**
```python
thislist = ["apple", "banana", "cherry"]
mylist = thislist[:]
print(mylist)
```
