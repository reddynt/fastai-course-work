```python
def change(x, y):
    x = y
    
def static():
    x = []
    for i in range(5):
        change(x, i)
    return x

static()
```




    []




```python
def change(x):
    x = 5
    
def static():
    x = 1
    change(x)
    return x

static()
```




    1




```python
"x" in globals()
```




    False


