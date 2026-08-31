# Introduction to Lists

* List is also sequence and it is mutable
* sequence means we can iterate,slice,len() function just like strings
* mutable we are going to change characters inside it

```py
fruits = ["apples","oranges","bananas"]
fruits[1] = "grapes"
print(fruits)
```
It will update at 1th index position prints ['apples','grapes','bananas']

# Sequence Operations
1. Indexing : We can index from 0 to len(list) - 1 and also supports negative indexing


```py
fruits=["apples","grapes","poppins"]
print(fruits[0])
```
2. Slicing : Slicing is an operation done to take sublist from the list from i to j with j excluded


```py
fruits=["apples","ghu","poppins"]
print(fruits[0:2])
```
3. Length of List

```py
print(len(fruits)
```
# Type Specific Operations
1. append() : add the element to the list.
2. pop() : remove the last element from list.
3. remove() : remove element from list.
4. insert() : insert element from arbiratory position
5. extend() : extend the another list.

```py
fruits = ["apples","bananas"]
fruits.append("guavas")
print(fruits) # ['apples','bananas','grapes']
fruits.insert(1,"papaya")
print(fruits) # ['apples','papaya','bananas','grapes']
fruits.pop()
print(fruits) # ['apples','papaya','bananas']
```
# Nesting 
Nesting is the one of thing supported by lists 

```py
mat = [[1,2,3],[4,5,6],[7,8,9]]
```
It can contain anything any deep inside the list 

Even list can contain dictionary , set , another nested list as deep as possible

# Comprehension

Comprehension is the one of the way to write lists or express list 

```py
[ x for x in range(12)]
```
This code represents range() function which takes x-> y-1 is converts to list 

```py
[x for x in range(12) if x % 2 == 0]
```
We can also include conditions inside the Comprehensions

```py
mat = [ [1,2,3] , [4,5,6] ,[7,8,9]]
print([ row[1] for row in mat])
```
Output : [2,5,8]

# Bounds Checking 
Although the list does not have fixed size

We can only access indexes from 0 to len(list) - 1 beyonds won't work 

It throws IndexError becuase Python peforms bound checking 

