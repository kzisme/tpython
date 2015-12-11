Think Python || Chapter 7 - Iteration
=======================

In Python it is possible to make more than one assignment to the same variable.
A new assignment makes an existing variable refer to a new value (and stops
referring to the old one)

```
kevin = 5
print kevin,
kevin = 9
print kevin
```

This will output 5 then 7 because we used **multiple assignment** on our
variable.

``x = x+1`` means "get the current value of x, add one and update x with the
new value.

Before using variables you must first **initialize** it.

The first loop construct is a while statement.

```python
def countdown(n):
    while n > 0:
        print n
        n = n-1
    print 'Blastoff!'
```

You are also able to use the ``break`` keyword to break out of the loop.  

