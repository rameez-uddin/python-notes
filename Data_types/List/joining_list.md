## Join two lists:

it is very simple to join the lists
**Example:**
```python
list1 = ["a", "b", "c"]
list2 = [1, 2, 3]

list3 = list1 + list2
print(list3)
```
### Output:
```
['a', 'b', 'c', 1, 2, 3]
```
## Appending the elements of list1 to list2 one by one using for loop:

```python
list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

for x in list2:
  list1.append(x)

print(list1)
```
## Extend Method:

Use the extend() method to add list2 at the end of list1:

```python
list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

list1.extend(list2)
print(list1)
```