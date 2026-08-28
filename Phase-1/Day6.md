# Immutability 
Immutability refers to the once assigned cannot change in-place

```py
name = "Maya"
name[0] = "K"
```
Above code will produce error 

* Because Strings are immutable in python in which they cannot change characters internally
* It was make sure that original characters preserved until whole was updated


* Mutable built in types : list , dict,set
* Immutable : numbers,string, float,tuples

# Type Specific Methods

* Type Specific methods are the methods which are specific to particular built in type.
* methods are one which triggers when call by parthensis

## for example 
## find() method
```py
# find() method
fruit = "Papaya"
print(fruit.find("a")) # 1
print(fruit.find("z")) # -1
```

# Getting Help
In order to get help for this method we have dir() function

```py
name = "Jagan"
dir(name)
```
help() function will gives when it is object and or its type unless it is empty
```py
name = "Laran"
help(name)
```
help() functions explains something brefily

# Other ways to code 
""" : used for multiline strings

special characters backslash is also used

