## To insert a list item at a specified index, use the insert() method.

The insert() method inserts an item at the specified index:
```python
thislist = ["apple", "banana", "cherry"]
thislist.insert(1, "orange")
print(thislist)

```
## Extend List.

To append elements from another list to the current list, use the extend() method.

```python
thislist = ["apple", "banana", "cherry"]
tropical = ["mango", "pineapple", "papaya"]
thislist.extend(tropical)
print(thislist)
```
## Add any iterable

The extend() method does not have to append lists, you can add any iterable object (tuples, sets, dictionaries etc.).

add elements of a tuple to list

```python
thislist = ["apple", "banana", "cherry"]
thistuple = ("kiwi", "orange")
thislist.extend(thistuple)
print(thislist)
```
## Remove List Item.

use pop method to remove from the specified index

```python
thislist = ["apple", "banana", "cherry"]
thislist.pop(1)
print(thislist)
```
- If you do not specify the index, the pop() method removes the last item.

The del keyword also removes the specified index:

```python
thislist = ["apple", "banana", "cherry"]
del thislist[0]
print(thislist)
```
### Delete the intire list using del

```python
thislist = ["apple", "banana", "cherry"]
del thislist
```
- this will delete the entire list

