# String 
* String are immutable sequence of characters
* They can be text or bytes of information

# Immutablity
It tells that the characters cannot be changed in-place

# Sequence:

It was expressed as ordered by indexes

# String Literals
Ways to express Strings

1. Single quotes and Double quotes
2. Triple quotes
3. Escape sequences
4. Raw Strings

# Single and Double quotes
* Single and Double quotes are used in Strings but they are same
* Why they are used to avoid backslash one used on another
* They represent same object

```py
name = 'Python'
Name = "Python"
```
* If they start with one type end with same type of quotes

# Triple quotes and Multiline Strings

* Triple quotes are intended to describe multiline strings 
* They put automatically newline between lines except at last

* Triple quotes are also used in documentation comments(docstrings)
* They are also used when we inject other code like HTML,XML;

```py
mul = """ The book
is deeply understnfable
hello"""
````

# Escape Sequences

* Escape Sequences are sequences in which characters followed by backslash encoded into single character as encoding code point 
* \n : code point : 10 which is actually newline
* Unicode is the standard which denotes the character to code point , code point may be stored in more than a byte
* len() function counts the number of code points
* Strings are naturally sequences of code points


```py
a = 'a\n'
```

# Raw Strings

* During giving File path for Windows or Regex Expressions we need to show backslas should be supressed
* Such time r prefix is used which is called raw strings
* But it still it ends only with even number of backslashes

```py
name = r'C:/hello'
```

