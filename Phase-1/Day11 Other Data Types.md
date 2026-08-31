# Other Data Types

## Sets
* Set is unordered collection of immutable
* Set is mutable
* Set does not supports duplicates
* set is hashable
```py
empty_set = set()
num = {1,2,3,4}
set.add(5)
set.add(4) # wont add anything
set.remove(3)
```
### Set Operations
1. & (Intersection)

 Elements present at the both sets

```py
A = {1,2,3}
B = {3,4,5}
print(A & B) # {3}
```

2. | (Union)

Elements in both sets

```py
A = {1,2,3}
B = {3,4,5}
print(A | B) # {1,2,3,4,5}
```
3. - (difference)
Elements present in A but not present in B
```py
A = {1,2,3}
B = {1,2,5,6} 
print(A - B) # {3}
```
4. > (subset)
checks A is subset of B
```py
A = {1,2,3}
B = {1,2,3,4,5,6}
print(A > B) # A is subset of B
```
# Booleans and None
* Boolean : 1 for True and 0 for false 
* 0,0.0,[],{},"",False are all falsy values and others are truthy values

```py
isControl = True
print(isControl)
```

* None represents the placeholder of nothing.

```py
isFunction = None
```
# Type function

*  type() function represents the type of the data which represents type class.
* type() checks the type of the object.

```py
data = 12
print(type(data))
```
Type Hinting 

* Like TypeScript type hinting which lets only for user to know this data.
* Type Hinting is not used by python

```py
x:int = 1
```
# User Defined Objects

* User Defined in class in which has properties and methods

```py
class Person:
   pass
```
