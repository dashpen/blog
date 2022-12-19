---
toc: true
layout: post
description: First Presentation
categories: [markdown]
title: First Presentation
---
{% include lessonTable.html %}

# Variables
Variables are ways to store data in a program and can be manipulated in many ways
## Naming
Make variable names:
- not too long
- descriptive
- without breaking syntax rules (dashes, spaces, colons, etc)
## Types
Different data types can store different types of data. The types of data are
- Integer: A whole number
- String: A collection of characters
- Boolean: Binary true or false
- List: Can store many variables in one variable where you can access everything
## Assigning
Data can be manipulated by assigning it to something else. You can also just change the data a little bit with different assigning operators.
- =: Sets a variable to something else
- +: Adds something
- -=: Subtracts something
- *= Multiplies something
- /= Divides something
- **= Does something to a power
## Lists
Lists are a very easy way to store a lot of data USE THEM

## Lists Activity
```
arr = ["green", "red", "pink", "purple", "blue", "brown"]
for el in arr:
    print(el)
```
## Homework
```
# Database
arr = []
go = True
while(go):
    re = input("What do you want to do with the database?: ")
    if(re == "add"):
        arr.append(input("What do you want to add?: "))   
    if(re == "remove"):
        arr.remove(input("What do you want to remove?: "))   
    if(re == "change"):
        i = int(input("What element do you want to change? (number): "))
        arr[i] = input("What do you want to change it to?: ")
    if(re == "stop"):
        go = False
print(arr)
```