# Dictionary

* Dictionary is the data structure
* Dicitonary is not sequence but it is key-value pairs
* Dictionary is Mapping
* Dictionary is not used by relative postion and mapped by key-value pairs

# Mapping Dictionary
* Dictionary is mapped by key-value pairs
* Accessed by key

# Creating Dictionary

## Way 1
```py
person = {} # empty dictionary
person['name'] = 'Karen'
person['age'] = 25
person['salary'] = 25_000
print(person)
```

## Way 2
```py
person = {
  'name' : 'Karen',
  'age' : 25,
  'salary' : 25_000
}
```

# Way 3
```py
person = dict(name='Karen',age=25,salary=25_000)
```

# Way 4
```py
person = dict(zip(['name','age','salary'],['karen',25,25_000]))
```

zip function : 
list1 and list2 should be same length or else throw error

# Nesting 

Dictionary nesting can be found because you can have dictionary inside another dicitonary

```py
person = {
  'name': {
     'first' : 'Sam',
      'last' : 'Altman'
  }
  'age' : 50,
  'details': {
    'name' : 'thiru',
   }
}
```
# Missing Key If Tests 

Dictionary keys are present it can access 

If Keys not present ,  throws KeyError 

```py
if 'name' not in person['name']:
   print("name was not found")
```
# Iteration : for loops

* keys() : keys in dictionary
* values() : values in dictionary
* items() : key-value pairs in dictionary

```py
for key in person.keys():
   print(key)
```
```py
for value in person.values():
   print(value)
```

```py
for key , value in person.items():
   print(key,value)
```

