Think Python || Functions
=======================

Functions are named sequenecs of statements that perform a computation.
Functions are able to be 'Called' later and reused. 

One simple example of a function would be:

```
type(32)
#Output <type 'int'>
```

Python also includes type-conversion functions.  

int -> floating point (The decimal point gets chopped off)
```
int(3.99999)
#Output 3
```
floats -> integers 
```
float(32)
#Output 32.0
```
```
float('3.14159')
#Output 3.14159
```

strings -> floating points

str -> strings 
```
str(32)
#Output '32'
```
Python makes use of **Modules** - Modules are files that contain a collection
of related functions.

To use a module you must first import it like so:
```
import math
```

You are then able to use dot-notation to call functions within an imported
module.
```
math.pi - The program would grab the .pi value from the math module 
```
Aside from the many built in functions in Python you are also able to write
your own functions!

```
def print_words():
    print "There she goes..."
    print "There she goes again!"
```
**def** is a keyword used to denote that we are creating a function.
**print_words** is the function name.  The first line of the function is called
the **header** and the rest of the function is called the **body**.

The body must be indented - and by convention an indent is equal to four
spaces.  Single quotes and double quotes accomplish the same thing, but if a
string contains an apostrophe it is necessary to surround the string in double
quotes.  

Functions are able to call other functions.

```
def repeat_words():
    print_words()
    print_words()
```

If you were to then call 
```
repeat_words()
```
It would output 

```
There she goes...
There she goes again!
There she goes...
There she goes again!
```

Parameters and Arguments 

Inside functions arguments assigned to variables are called parameters.

```
def print_twice(Kevin):
    print Kevin
    print Kevin
```

When writing and calling functions it is important to keep scope in mind.  When
a variable is used within a function it is **local** to that function.

Two types of functions we have seen so far are
    1. Fruitful functions - value returning 
    2. Void functions - not value returning 

Why use functions?
* Easier to group statements
* Removes repetitive code 
* Easier debugging since parts of the code are seperated
* Functions are reuseable

You are also able to import modules using the keyword **from**.

Using **from** you are able to access constants like pi directly like so:
```
from math import pi
print pi
#Output 3.14159265359
```

You're also able to import _everything_ in the module using the * operator.
```
from math import *
```


    

























