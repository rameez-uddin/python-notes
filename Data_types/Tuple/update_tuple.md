# Change tuple values:

**Once a tuple is created, you cannot change its values. Tuples are unchangeable, or immutable as it also is called.**

**But there is a workaround. You can convert the tuple into a list, change the list, and convert the list back into a tuple.**

### Example:
 convert the tuple into list and then change the value:

```python
x = ("apple", "banana", "cherry")
y = list(x)
y[1] = "kiwi"
x = tuple(y)

print(x)
```
# Add items:

there is no append method for tuples, so 
1.  Convert into a list: Just like the workaround for changing a tuple, you can convert it into a list, add your item(s), and convert it back into a tuple. 

```python
thistuple = ("apple", "banana", "cherry")
y = list(thistuple)
y.append("orange")
thistuple = tuple(y)
```
2.  Add tuple to a tuple. You are allowed to add tuples to tuples, so if you want to add one item, (or many), create a new tuple with the item(s), and add it to the existing tuple

```python
thistuple = ("apple", "banana", "cherry")
y = ("orange",)
thistuple += y

print(thistuple)
```
# Remove items:

we will use the same approch to remove the items:

```python
thistuple = ("apple", "banana", "cherry")
y = list(thistuple)
y.remove("apple")
thistuple = tuple(y)
```
**or delete the tuples using the `del` keyword**