---
title: "Time Complexity"
---
## Big O notation
This notation expresses the worst-case time complexity as a function of n
Simpler terms: The notation represents the worst run time complexity of your code 
### O(1)
```
a = 5
b = 7
c = 4
d = a + b + c + 153
```
The code is O(1) because it executes a constant number of operations
The code only loops 1 time

### O(n)
```
for i in range(1, n + 1):
	pass # constant time code here
```
Following code is O(n) time complexity as it executes n times 
```
for i in range(5 * n + 17):
	pass # constant time code here

for i in range(n + 457737):
	pass # constant time code here
```
This is also an example of code that's O(n) time complexity it executes or loops n times

### O(nm)
```
for i in range(n):
	for j in range(m):
		pass # constant time code here
```
To calculate the time complexity of this code we multiply the time complexity of both the loops
The time complexity is O(nm) because the outer loop runs O(n) and inner loop runs O(m)

### O(n$^2$)
```
for i in range(n):
	for j in range(n):
		pass # constant time code here

for i in range(n + 58834):
	pass # more constant time code here
```
If an algorithm contains multiple blocks it's time complexity is the worst time complexity out of any block, the following code is O(n$^2$)

### O(n$^2$ + m)
```
for i in range(n):
	for j in range(n):
		pass # constant time code here

for i in range(m):
	pass # more constant time code here
```
This code is O(n$^2$ + m) because it contains 2 blocks of complexity **O(n$^2$)** and **O(m)** and neither of them is a "lower order function"


