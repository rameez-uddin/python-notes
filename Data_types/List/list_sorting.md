# Sort List Alphanumerically:
- List objects have a sort() method that will sort the list alphanumerically, ascending, by default:

### Example

```python
thislist = ["orange", "mango", "kiwi", "pineapple", "banana"]
thislist.sort()
print(thislist)
```
### Output
```
['banana', 'kiwi', 'mango', 'orange', 'pineapple']
```
- Sort the list numerically:

```python
thislist = [100, 50, 65, 82, 23]
thislist.sort()
print(thislist)
```
### Output

```python
[23, 50, 65, 82, 100]
```
## Sort the list in descending order:

- To sort descending, use the keyword argument reverse = True:

```python
thislist = ["orange", "mango", "kiwi", "pineapple", "banana"]
thislist.sort(reverse = True)
print(thislist)
```
# Customize Sort Function: 

 We use the keyword `key = funtion`

 ```python
def myfunc(n):
  return abs(n - 50)

thislist = [100, 50, 65, 82, 23]
thislist.sort(key = myfunc)
print(thislist)


```
### Explanation:
1. **Function `myfunc(n)`**:
   - This function takes a number `n` and returns the absolute difference between `n` and `50`. So, for example:
     - `myfunc(100)` returns `|100 - 50| = 50`
     - `myfunc(65)` returns `|65 - 50| = 15`

2. **Sorting with a Custom Key**:
   - In the `thislist.sort(key=myfunc)` call, the `key` parameter specifies that each element in `thislist` should be passed through `myfunc()`, and the list is then sorted based on the result of `myfunc()` for each element.
   
3. **How the List is Sorted**:
   - It sorts the list based on how close each number is to 50. So, the element with the smallest difference from 50 will come first, and the largest difference last.

### Output:
For your code:
```
[50, 65, 23, 82, 100]

```
This is because:

- `50` has a difference of `0` from `50`
- `65` has a difference of `15`
- `23` has a difference of `27`
- `82` has a difference of `32`
- `100` has a difference of `50`

# Reverse Order:

Through this we can reverse the order of the elements in a list.

```python
thislist = ["banana", "Orange", "Kiwi", "cherry"]
thislist.reverse()
print(thislist)
```
