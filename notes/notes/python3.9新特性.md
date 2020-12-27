# python3.9新特性

#### 函数声明中/

```python
def test_func(a, /, b):
    print(a, b)


test_func(1, 2)
```

/之前的参数不能以 name=value 这种形式传参

```python
 def f(a, *, b): ... *
```

*之后的必须以name=value 的形式传参