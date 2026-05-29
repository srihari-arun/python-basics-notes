📘 While Loop - Python Notes
==============================================

A beginner-friendly set of notes explaining the concept of while loops in Python with examples and practice programs.

----------
🎯 Purpose
----------

*    Master and acquire proficiency in the while-loop concept
    
*    Understand real-world applications of the while-loop
    
*   Expand Python knowledge
    
*   Build consistency in coding practice
    
-----------
🎯 Contents
-----------

*   What is a while-loop?
    
*   Syntax of while-loop
    
*   Examples and mini-projects
    
*   Some other extra functions

--------------------------
🚀 What is a while-loop?
--------------------------
A while loop is a loop that keeps running while a condition is true, and stops when it becomes false.

It can run infinitely as long as the condition stays true

--------------------------
🚀 Syntax is a while-loop
--------------------------
```
while condition:
    # code to repeat
```

-------
💻 Exercise - 1: Print numbers from 1 to 10
-------
```python
counter = 1
while counter <= 10:
    print(counter)
    counter += 1 # If we did not include this, the program would print '1' continuously forever.
print(" ")
```
The output is as follows:

<img width="1804" height="658" alt="image" src="https://github.com/user-attachments/assets/ade2753d-1ce2-4831-a53e-931673b77306" />

-------
💻 Exercise - 2: Print numbers starting from 1, doubling until 1000
-------

```python
num = 1
while num <= 1000:
    print(num)
    num *= 2 # The numbers keep on doubling, but only until 512, since the maximum limit is 1000.
print(" ")
```
The output is as follows:

<img width="1794" height="704" alt="image" src="https://github.com/user-attachments/assets/5a5fcc0a-9434-4192-b01f-3b1178fd0f87" />
    
--------------------------
🚀 New functions to learn:
--------------------------

1.   ``` .remove() ``` is a method primarily used with sets and lists to delete a specific item by its value instead of its index.
    
2. ``` .clear() ``` is used to remove all items/elements from a mutable collection
    
3.  ```
     a = [1, 2, 3]
     b = a
     a = []
     print(b)
    ```
    In this case, the output will be \[1, 2, 3\] because only 'a' is reset to a new empty set, while 'b' still points to the     original data.
    
4.  deque (pronounced 'deck') is the short form for double-ended queue. We will study this later, as this is complex.
    
5.  Dictionaries and sets are represented in '{ }', so we differentiate them using their content structure within the braces.
    
   

⭐ Part of my Python learning notes repository.
