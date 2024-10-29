
**With list comprehension you can do all that with only one line of code:**

### Example
```python
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

newlist = [x for x in fruits if "a" in x]

print(newlist)
```
## Syntax:

```
newlist = [expression for item in iterable if condition == True]
```
## Another Example:

```python
 fruits = ['apple', 'aple', 'appel', 'apple', 'appple', 'apple', 'aplpe',
 'apple', 'appe', 'aple', 'apple', 'appel', 'apple', 'appell', 
 'apple', 'appl', 'applle', 'apple', 'appple', 'apple', 'aaple', 
 'apple', 'apple', 'appl', 'apple']

 newlist = [x for x in fruits if x == "apple"]
 print(newlist)
```
  This will filter out the strings according to the condition applied..!!   

# Range func in Iterable:
## Example:
```python
newlist = [x for x in range(10) if x < 9]
print(newlist)
```