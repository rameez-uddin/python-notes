## Range function
## Syntax:

```python
range(start, stop, step)
```
- start: (Optional) The starting point of the sequence. By default, it is 0.
- stop: (Required) The endpoint of the sequence (not included in the range).
- step: (Optional) The difference between each number in the sequence. Default is 1.

## Example:

```python
for i in range(1, 10, 2):
    print(i)

```
- This generates numbers starting from 1, incrementing by 2 each time, up to 9.
 
**Result:**
```output
1
3
5
7
9
```