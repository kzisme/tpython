Think Python || Chapter 5 Conditionals and Recursion
=======================

Modulus Operator is denoted as % in Python and works on integers and yeilds the
remainder when the first is divided by the second.  

```
remainder = 7 % 3
print remainder
#Output 1
# 7 / 3 is 2 with only 1 left over
```
You are able to use the modulus operator for many useful things.

Boolean Expressions are expressions that evaluate to either true or false. 

Using the == relational operator we are able to compare values.
```
5 == 5
True
#True and false are special values that belong to **bool**
```

The other relational operators are as follows:
```
      x != y               # x is not equal to y
      x > y                # x is greater than y
      x < y                # x is less than y
      x >= y               # x is greater than or equal to y
      x <= y               # x is less than or equal to y
```

There are also three logical operators.

* and 
* or
* not 

In programming we use conditional statements to control program flow.
```
if x > 0
    print 'x is positive'
```

Within conditional execution you are able to set alternate executions.
```
if x%2 == 0:
    print 'x is even'
else:
    print 'x is odd'
#Each conditional flow is considered a **branch**
#If the remainder of x / 2 is even the first branch is executed
#If the remainder is odd the second branch is executed
```

It is also possible to nest conditional statements inside one another.  
```
if x == y:
    print 'x and y are equal'
else:
    if x < y:
        print 'x is less than y'
    else:
        print 'x is greater than y'
```

Recusion is the idea that a function can call itself. 

def countdown(n):
    if n <= 0:
        print 'Blastoff!'
    else:
        print n
        countdown(n - 1)

countdown(3)
#Output
#3
#2
#1
#Blastoff!
```

If a recursive function never reaches a base case it will recurse indefinately.  

In Python 3 we are able to accept user input using **input**
```
text = input()
```

If the input is an unexpected type the program will throw an error, so you must
convert types.  

















