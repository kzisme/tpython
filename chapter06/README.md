Think Python || Chapter 6 - Fruitful Functions
=======================

Fruitful functions are functions that have **return value**  So far we have only
written void functions - or functions that return no values

Take make debugging functions easier we often make use of **temporary
variables**

All Python functions that return ``None`` whenever they do not return another
value.  

As with most branching techniques you may unknowingly create unreachable code
based on the provided logic.  This is where you get to debug your functions!

You are also able to place ``return`` statements within for loops to give
control back to the function

```python
def find_first_2_letter_word(xs):
    for wd in xs:
        if len(wd) == 2:
            return wd
    return ""
```

```
#Output >>> find_first_2_letter_word(["This", "is", "a", "dead", "parrot"])
# >>> 'is'
```

Functions are able to call other functions as well.

Boolean functions are functions that return a boolean value ``true`` or
``false``.

```python
def is_divisible(x,y):
    return x % y == 0
```


