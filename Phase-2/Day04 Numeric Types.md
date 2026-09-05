# Underscore separators in Numbers

```py
a = 12_000
```

* underscores between the numbers is discarded when reading python
* but _ before or after number cause error
* It can be used in floating point and complex numbers

```py
n = 12_000
p = 12_000j
q = 12.32_34_45
```

```py
int(12.32_32)
```

# Other Built in Tools 

## Math module
```py
import math
print(math.pi)
print(math.sqrt(5))
```

##  Random module

```py
from random import random
print(random.randint(1,10))
```

## Stastics Module

```py
import stastics
print(stastics.mean([1,2,3,4,5]))
```

# Bitwise Operators

The Operators on bit 

1. Shift Operator
2. Bitwise or,and,not operator

```py

a = 12
b = 2
print(a << b)
```
