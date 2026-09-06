# Set objects

Set Objects is defined the {} in which it is unordered collection of immutable elements

1. Sets itself is mutable
2. They can store only immutables not lists or dictionaries
3. tuples with immutable things inside is allowed

## Empty Set Creation

```py

empty = {}
```

## Set with Literal

```py

num = {1,2,3,4}
```
## add , remove methods

```py

num = {1,2,3,4}
num.add(1) # nothing happend
num.add(23) # add 23

num.remove(2) # remove 2
num.remove(2) # key error

```

## Set Operations

1. Union  : Include the elements without dupicates
```py
a = {1,2,3.4}
b = a.union({3,4,6,7,8})
c = a | {3,4,6,7,8}
print(b)
print(c)
```
2. update method  : Include and update the set without duplicate elements
```py
a = {1,2,3.4}
a.update({3,4,6,7,8}) # we cam also use |= union and update
print(a)
```
3. Difference : Present in A not in B
```py
a = {1,2,3.4}
b = a.difference({3,4,6,7,8}) # we cam also use (a-b) for difference
print(b)
```
4. Difference update : Difference and update it to A
```py
a = {1,2,3.4}
a.difference_update({3,4,6,7,8}) # we cam also use -= differene and update
print(a)
```

5. Intersection : Include only the elements present at both
```py
a = {1,2,3.4}
b = a.intersection({3,4,6,7,8})
c = a & {3,4,6,7,8}
print(b)
print(c)
```
6. Intersection and update  : Include only elements present at both and update it to first set
```py
a = {1,2,3.4}
a.intersection_update({3,4,6,7,8}) # we cam also use &= intersection and update
print(a)
```
7. Symmetric Difference : present on sets but not on both
```py
a = {1,2,3.4}
b = a.symmetric_difference({3,4,6,7,8}) # we cam also use (a^b) for symmetric difference
print(b)
```
8. Symmetric Difference upate : update the set with symmetric difference
```py
a = {1,2,3.4}
a.symmetric_difference_update({3,4,6,7,8}) # we cam also use ^= symmetric differene and update
print(a)
```

9. Superset and subset

```py
a = {1,2,3,4,5}
b = {4,5,6}
print(a.issuperset(b)) # a > b
print(a.issubset(b)) # a < b
```

## Frozen Set
Frozen set means it never changes it is  immutable

1. Set does not have ability to store another set
2. Set stores frozen set


Other List and Tuples in sets uses ```*``` to unpack it

```py
frozenset(set())
a = {*[1,2,3,4],(1,2,3)}
```

## Boolean expression
1. It is subclas of int
2. True - 1
3. False - 0
4. True + False = 1
5. False + 1 = 1

```py
a = True
```
Boolean  tells it is yes or no like thing 
