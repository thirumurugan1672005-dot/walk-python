
# Introduction to Strings 

* Strings are first sequence of one character strings
* Strings are sequence so it have some property
* len() : function is access the length of string

```py
name = "MaryLoven"
print(len(name))
```
## Characters are accessed by indexes from 0 to len(string)-1
```py
name = "Mary"
print(name[0])
print(name[len(name)-1])
```

## We can also use negative index to access from right to left 
```py
name = "Jhonson"
print(name[-1]); # prints last letter
print(name[-len(name)]) # prints first letter
```

# Concatenation and Repetition
* Concatenation (+) -> Add The Strings
* Repetition (*) -> Repeat the Strings

  Here we see + and * acts different with numbers and strings exhibits different behaviour which is referred as polymorphic
