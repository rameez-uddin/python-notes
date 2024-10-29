# While loop:
### The while loop is used to execute a block of code as long as the condition is true.

**Example:**
```python
i = 1
while i < 6:
  print(i)
  i += 1
```
**Output:** 1, 2, 3, 4, 5
### The while loop will continue to execute as long as the condition `i < 6` is

**Note: remember to increment i, or else the loop will continue forever.**

## Break Statment:

**With the break statement we can stop the loop even if the while condition is true:**

```python
i = 1
while i < 6:
  print(i)
  if i == 3:
    break
  i += 1

```
* Exit the loop when i is 3.

## Continue Statment:
* Continue to the next iteration if i is 3

```python
i = 0
while i < 6:
  i += 1
  if i == 3:
    continue
  print(i)
```
# Else keyword in loops:

* The else keyword in a for loop specifies a block of code to be executed when the loop is finished:

```python
for x in range(6):
  print(x)
else:
  print("Finally finished!")
```  
**Note: The else block will NOT be executed if the loop is stopped by a break statement**

## Pass statement:

- for loops cannot be empty, but if you for some reason have a for loop with no content, put in the pass statement to avoid getting an error.

```python
for x in [0, 1, 2]:
  pass
```  