# Numeric types  and Expressions

* In Python we can use numbers and there are similar kind of objects

Numeric Types

+ Integer
+ Floating point
+ Decimal with fixed precisions
+ Fractions objects
+ Sets objects
+ Complex numbers
+ Utility modules like cmath,math,random,stastics
+ Booleans (True or False)


Integers 
- Integers are whole numbers and negative integers
- They can also represented by hexadecimals ,octal,binary
floating point numbers
- They have fractional part
- Sometimes have optional e or E exponent
complex numbers
- real part + imaginary part
- both are comprises of floating point numbers
- real part is optional
- imaginary part is j or J

Hexadecimals 
hex(integer) : hex string it contains 0x or 0X followed by (0-9) and (A-F) upper or lower case
Octal
oct(integer) : oct string it contains 0o or 0O followed by 0-7
Binary
bin(integer) : binary string which contains 0b or 0B followed by 0 or 1

int(str,base)
* base : 2 for binary
* base : 8 for octal
* base : 16 for hexadecimal
converts into integer

# Expression Operators

____________________________________________________
  - []   : Lists or comprehensions
  - {} : dictionary 
  - () : tuple 

________________________________________________________

- .attr : attribute
- x() : method call
- x[i] : indexing
- x[i:j:K] : slicing

___________________________________________________________

- await x : Async functions
______________________________________________________________

- x**y : Exponentation

_________________________________________________________________

- +x : identity
- -x : negation
- ~x : bitwise not

__________________________________________________
x @ y only used for matrix multiplication
__________________________________________________
x // y: floor division
x / y : division
x * y : multiplication or repetition
__________________________________________________________
x+y addition or concatenation
x-y subraction or set difference
_____________________________
x <<y : left shift
x >>y : right shift
_____________________
x & y bitwise and or set intersection
______________________________
x^y : set symmetric difference & bitwise xor
____________________________________________
x|y : set union or dictionary union or bitwise or
______________________________________________
in or not in : membership
is or is not : object identity
x<y , x<=y ,x>y or x>=y : comparison
x==y , x!=y equality checking
_________________________________________
not x : not operator
_____________________________________
x and y : and operator
_____________________________
x or y : or operator
____________________________
x if y else x : ternary
_______________________
lambda expressions
____________________________
x:y : assignmeent
_______________
yield x : yield function
________________________

Operators are written higher to lower precedence

In mixed operation operations higher precedence executed first or if the operators have same precedence then execute from left to right.

Exponentation occurs right to left


# Use of () parthensis
However Parthensis can override the precedence 

In Python expression inside () executed before outer the parthensis 

Hence parthensis grouped preferred over for readability


# Mixed types

1. python int and float can be do operations
2. if any of them complex result is complex
3. if any of them float result is float
4. else int

Python during operation it becomes compicated type and done the operation among numbers

This type conversion only work between numeric literals

Operations between other type boundaries throw error

int() and float() can be used  explicilty to convert types


# Breif view of operator overloading

Because Python operators worked different based on objects hence operators are overloaded

Polymorphism behaviour is exhibited among operators hence operators are overloaded


