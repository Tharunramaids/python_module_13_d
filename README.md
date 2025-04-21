# Deque Implementation using `collections.deque` in Python

## Aim
To implement a double-ended queue (deque) using Python's `collections.deque` and demonstrate appending elements to both ends of the deque.

## Procedure
1. Import `deque` from the `collections` module.
2. Create an empty deque.
3. Accept 3 integer inputs from the user and append them to the **right** of the deque.
4. Use `appendleft()` to insert additional elements at the **left** (front) of the deque.
5. Display the final state of the deque.

## Program

```python
from collections import deque

# Create empty deque
dq = deque()

# Append 3 elements from user input to the right
for i in range(3):
    iop = int(input())
    dq.append(iop)

# Append elements to the left (front)
dq.appendleft(14)
dq.appendleft(15)

# Output the final deque
print("The deque after appending is :")
print(dq)
```
## output
![image](https://github.com/user-attachments/assets/b003dc8d-f790-42e0-bd96-95f1a4685a2a)

## Result
The program successfully demonstrates insertion of elements at both the front and rear ends of a deque using collections.deque.
