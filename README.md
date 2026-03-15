# Print 1 to 100 using Recursion

This Python program prints numbers from 1 to 100 without using loops.

## Code

```python
def print_numbers(n):
    if n > 0:
        print_numbers(n-1)
        print(n)

print_numbers(100)
```
##Output
1
2
......
100
## Concept Used
- Recursion
