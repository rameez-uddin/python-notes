# Python Set Methods

## 1. `add()`

-   **Use case**: Adds a single element to the set.

-   **Syntax**: `set.add(element)`

    2\. update()

-   **Use case**: Adds multiple elements from another set or iterable.

-   **Syntax**:` set.update(iterable)`

3\. remove()

-   **Use case**: Removes a specific element. Raises KeyError if the
    element is not found.

-   **Syntax**: `set.remove(element)`

## 4. discard()

-   **Use case**: Removes a specific element without raising an error if
    the element is missing.

-   **Syntax**: `set.discard(element)`

5\. pop()

-   **Use case**: Removes and returns a random element from the set.
    Raises KeyError if the set is empty.

-   **Syntax**: `set.pop()`

6\. clear()

-   **Use case**: Removes all elements from the set, leaving it empty.

-   **Syntax**: `set.clear()`

7\. union()

-   **Use case**: Returns a new set containing all unique elements from
    both sets.

-   **Syntax**: `set1.union(set2)`

8\. intersection()

-   **Use case**: Returns a new set with elements common to both sets.

-   **Syntax**: `set1.intersection(set2)`

9\. difference()

-   **Use case**: Returns a new set with elements in the first set but
    not in the second.

-   **Syntax**: `set1.difference(set2)`

10\. symmetric_difference()

-   **Use case**: Returns a new set with elements in either set but not
    both.

-   **Syntax**: `set1.symmetric_difference(set2)`

11\. issubset()

-   **Use case**: Checks if all elements of the set are in another set.

-   **Syntax**:` set1.issubset(set2)`

12\. issuperset()

-   **Use case**: Checks if the set contains all elements of another
    set.

-   **Syntax**: `set1.issuperset(set2)`

13\. isdisjoint()

-   **Use case**: Checks if two sets have no common elements.

-   **Syntax**: `set1.isdisjoint(set2)`

14\. copy()

-   **Use case**: Returns a shallow copy of the set.

-   **Syntax**:` set.copy()`

15\. frozenset()

-   **Use case**: Returns an immutable version of the set.

-   **Syntax**: `frozenset(iterable)`
