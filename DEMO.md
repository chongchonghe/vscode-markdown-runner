# Demo of extension's features

```python
def f(n):
    if n <= 0:
        return 0
    if n == 1:
        return 1
    return f(n - 1) + f(n - 2)

print([f(i) for i in range(10)])
```
