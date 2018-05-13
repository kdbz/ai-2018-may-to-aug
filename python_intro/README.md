# Python introduction

## Introduction

Python is a modern, robust, high level programming language. It is very easy to pick up even if you are completely new to programming. 

Python, similar to other languages like matlab or R, is interpreted hence runs slowly compared to C++, Fortran or Java. However writing programs in Python is very quick. Python has a very large collection of libraries for everything from scientific computing to web services. It caters for object oriented and functional programming with module system that allows large and complex applications to be developed in Python. 

These lectures are using jupyter notebooks which mix Python code with documentation. The python notebooks can be run on a webserver or stand-alone on a computer.

To give an indication of what Python code looks like, here is a simple bit of code that defines a set $N=\{1,3,4,5,7\}$ and calculates the sum of the squared elements of this set: $$\sum_{i\in N} i^2=100$$


```python
N={1,3,4,5,7}
print('The sum of ∑_i∈N i*i =',sum( i**2 for i in N ) )
```

    The sum of ∑_i∈N i*i = 100


## Contents

This course is broken up into a number of notebooks (chapters).

* [00](00.ipynb) This introduction with additional information below on how to get started in running python
* [01](01.ipynb) Basic data types and operations (numbers, strings) 
* [02](02.ipynb) String manipulation 
* [03](03.ipynb) Data structures: Lists and Tuples
* [04](04.ipynb) Data structures (continued): dictionaries
* [05](05.ipynb) Control statements: if, for, while, try statements
* [06](06.ipynb) Functions
* [07](07.ipynb) Classes and basic object oriented programming
* [08](08.ipynb) Scipy: libraries for arrays (matrices) and plotting
    

This is a tutorial style introduction to Python. For a quick reminder / summary of Python syntax the following [Quick Reference Card](http://www.cs.put.poznan.pl/csobaniec/software/python/py-qrc.html) may be useful. A longer and more detailed tutorial style introduction to python is available from the python site at: https://docs.python.org/3/tutorial/

## @Credits
- [Rajath Kumar](https://github.com/rajathkumarmp/Python-Lectures) - The original author
- [Andreas Ernst](http://users.monash.edu.au/~andreas) - Updated notebook code compatibility for python3