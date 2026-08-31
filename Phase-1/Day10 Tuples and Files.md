# Introduction to Tuples 

1. Tuples are immutable in which contents will not be changed like string
2. It is sequence so indexing , slicing , concatenation can occur
3. But items inside can be mutable one like tuple may contain list which is mutable
4. It is nested
5. We can count and find in tuples
6. since there is nothing going to change we don't have overhead in any adding or deleting it comparatively faster peformance and consumes less memory

```py
fruits = ('apple','banana','oranges')
print(fruits[0])
print(fruits[1:])
```
```py
fruits = ['apple','oranges','bananas']
print(fruit.count('apple'))
print(fruit.find('apple')) # 0
```

# Introduction to Files
1. Files are the one in important in which most of them opened by open() function
2. There are different modes mainly w , r , a modes
3. w : write mode when we need to change entire thing or there is no such file exists
4. a : when file does not exists or you want to add next contents not change anything already present
5. r : when you want to read the file already exists
6. we should close the file in order to reduce consumption of resources or any memory overhead.

```py
f = open('file.txt','w')
f.write('Hello World')
f.close()
```
```py
f = open('hello.txt','r')
print(f.read()) # read as entire string
for f in f.readlines():
    print(f)
f.close()
```
read() : entire things as string

readlines() : read line by line
