# Header1
## Header2 
### Header3
Демонстрационный репозиторий 
- one 
- two
- three 

1. First 
2. Second 
3. Thrid 


```python
def fibonacci(max):        # генератор (а не функция, т.к. оператор return заменён на yield)
    a, b = 0, 1
    while a < max:
        yield a            # return a, + запоминаем место рестарта для следующего вызова
        a, b = b, a + b    # параллельное присваивание, которое выполняется одновременно и параллельно

for n in fibonacci(100):   # используем генератор fibonacci() как итератор
    print(n) 
```

![](https://img1.akspic.ru/originals/8/0/6/8/3/138608-anonimnye_narkomany-elektronnoe_ustrojstvo-haker-nebo-illustracia-720x1280.jpg)
