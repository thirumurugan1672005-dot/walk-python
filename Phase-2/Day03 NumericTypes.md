# Division operators

Division and Modulus 

1. ```/``` Operator
```py
a = 12 / 2
```
It is true division operator which results in floating point of number

2. ```//``` operator
```py
x = 12 // 2.0 # 6.0
y = 144/12.6
```

It is floor division in which it gives largest number smaller than result 

3. ```%``` operator

```py

a = 12 % 2
```

It results in remainder of the operands


4. divmod() function

divmod() function returns both quotient and remainder


# Floor vs Truncation

* Floor means the largest integer smaller than value
* Truncate means the simply discarding digits


```py

print(truncate(12/3.4))

import math
print(math.trunc(12/3.45))
```

```py

import math
print(math.floor(12/2.3454))
print(12//2.34556)
```


#  Complex Numbers

Complex numbers : real + imaginary part

imaginary part with j or J as suffix 

```py
z = 12+3j
y = 12+45j
print(z+y)
```

# Integer Precision

x = 2 ** 1000000000000000

print(x) // throws error 
```
ValueError: Exceeds the limit (4300 digits) for integer string conversion; use sys.set_int_max_str_digits() to increase the limit
```



