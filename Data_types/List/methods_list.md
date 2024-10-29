## 1. append():

adds an element at the end of the list.

```python
my_list = [1, 2, 3, 2]
my_list.remove(2)  # Removes the first '2'
print(my_list)  # Output: [1, 3, 2]
```
## 2. clear() :

removes all of the elements of a list

```python
my_list = [1, 2, 3]
my_list.clear()
print(my_list)  # Output: []
```
## 3. copy():

returns the copy of the list

```python
my_list = [1, 2, 3]
new_list = my_list.copy()
print(new_list)  # Output: [1, 2, 3]
```
## 4. reverse(): 
reverses the order of the list

```python
my_list = [1, 2, 3]
my_list.reverse()
print(my_list)  # Output: [3, 2, 1]
```
## 5. sort():
sorts the list in ascending order

```python
my_list = [3, 1, 2]
my_list.sort()
print(my_list)  # Output: [1, 2, 3]
```
## 6. count():
counts the number of occurance of an element in a list

```python
my_list = [1, 2, 2, 3]
count = my_list.count(2)
print(count)  # Output: 2

```
## 7. index():
returns the index of the element

```python
my_list = [1, 2, 2, 3]
count = my_list.count(2)
print(count)  # Output: 2
```
## 8. pop():
Removes and returns an element at the specified position. If no index is given, it removes the last item.

```python
my_list = [1, 2, 3]
popped_item = my_list.pop()  # Removes and returns the last element
print(popped_item)  # Output: 3
print(my_list)  # Output: [1, 2]
```
## 9. extent():
Adds all elements from another list (or iterable) to the end.

```python
my_list = [1, 2, 3]
my_list.extend([4, 5])
print(my_list)  # Output: [1, 2, 3, 4, 5]
```
## 10. insert

insets an element to specified position

```python
my_list = [1, 2, 3]
my_list.insert(1, 'a')  # Insert 'a' at index 1
print(my_list)  # Output: [1, 'a', 2, 3]
```