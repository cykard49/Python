### Everything is object in Python.

# String

"this is a string"

'this is too'

"""you can
do triple quotation
for multiple lines"""

'''or you can also 
do with single quotation
just like I did here'''

1 #this is integer
"1" #this is string

word = "Camera"
print (word)
#you will get "word" as an output

* to use capitalize method to make 1st string capital
word = word.capitalize(), gives CAMERA

#to concatenate additional letters to string
#word = word + " Shot", gives Camera Shot

#list slicing example: a=[start:end], where start includes element, end includes element before that 'end' element


# Numberic objects
* if you type simple number or decimal number with numerical sign, python will simply give you output

#example of interger : 5+5 gives 10

#example of decimal or float: 1.0 + 2.1 gives 3.1

#example of exponentiation: 4 ** 2 gives 16
* '^' symbol is not exponentiation symbol in python

* example of modulo (remainder after dividing one number by another):
* print (16 % 5) gives 1, which is the remainder

# List

* List has square brancket '[]'
* list can have any type of value, or sub-list inside it
* example: a = [1,2,"anything", 2.0, True, [2,4,'a']]

#list concatenation or adding
#example: a = a + ["better"] gives [1,2,"anything", 2.0, True, [2,4,'a'], "better"], this is adding "better" inside previous list a form line# 49 above
* above in line#52, 0th element=1, 1st element=2, 2nd element="anything", 3rd element=2.0, 4th element=True.. and so one
* it is like this because python count starts with 0th element

#list deletion or removal of element from list
#example: del(a[4]) gives [1,2,"anything", 2.0, [2,4,'a'], "better"], here 'True' is removed, which is the 5th elements of list, but python 4th element


# Dictionary
#exmaple of dictionary: x={'year':2021, 'money':20000}
#dictionary has key:value pairing

#concatination or adding value in dict example: x['state']='CA' gives x={'year':2021, 'money':20000, 'state':'CA'}

#to delete value from dict example: del(x['year']) gives x={'money':20000, 'state':'CA'}, where 'year' has been deleted


# Built-in function
 * to know the type of any value simply do 'type(value)'
 * example: type(1) gives integer
             type("this") gives str, which is string
             type (True) gives bool, which is boolean
             
 * round(value, nth-is optional)
 *example: 1.34 to round(1.34,1), gives 1.3
 *                 round(1.34), gives 1
 
 * example to sort List integer: d=[43,6,76]
                 to sort==> sorted(d), gives [6,43,76]
                 to sort with reversed==> sorted(d, reverse=True), gives [76,43,6]
                 
 * to know about built-in function: help(functionName) or ?<functionName>


# Methods:
* integer example:
          x = [2,4,'rt', '6']
          x.index('6'), gives 3, where '.index' is a method which will find index element number inside x.

* string example:
        y = "jake"
        y.capitalize(), gives Jake, where '.capitalize' would make first letter capital
        y.replace("j", "z"), gives "zake", where letter 'j' in 'jake' was replaced by letter 'z'
        
 * some methods depend on object types
 - example: y.replace() works, but x.replace() won't because y has string object, but x has mixed objects, which won't work for '.replace' method

# Jupyter Notebook tips

* any function with "%" in front of it, in a Jupyter notebook cell is called the magic line function
* % convert cell line as a linux or other terminal line, where you can type command
* example==> %cd c:users/Documents --> this line take you to the current directory
*            %pwd --> this command in a Jupyter notebook cell output pathway to currrent working directory, or shows current directory where you are now       


#in jupyter cell, if you ask it to print multiple output, it will only print the last one
#example by keeping below all in one cell:
- 5 - 5
- 3 + 2
- 2 * 3
* the output will be just 6, as it will just print '2 * 3' value
* solution: add 'print(<value>)' in each line


* to find methods availability for string object and to know what it does:
*           type object name in a cell, followed by period '.'
*           press tab key
*           scroll through list and select method
*           type '?'
*           run cell

# NOTES
* DO NOT WRITE PYTHON IN CAMELCASE (camelCase), JUST LIKE WE DO IN JAVA.
* '^' symbol is not exponentiation symbol in python.

* To import packages in python, we can do it in 4 different ways:
1. import <module_name>
2. from <module_name> import <name(s)>
3. from <module_name> import <name> as <alt_name>
4. import <module_name> as <alt_name>

- '=' in x=3, a='name', is called assignment.

* Built-in Functions and Methods are pre built code by other people, which you can help to solve our own problem.
* Having all built-in functions and methods in same python distribution, which we might not use in our project, can take a lot of memory and makes python application slow.
* Solution is to make packages, which is directory of the python scripts.
* Each script is a so-called module, which specify functions, methods and types.
* Thousands of python packages available online.
* Example:
- For Datascience package: NumPy
- For Data Visualization: Matplotlib
* Some packages are not available by default, so we need to install them.
* To install packages we can use 'pip', which is package maintainance for python.
- Go to https://pip.readthedocs.org/en/stable/installing/
- Download file 'get-pip.py'
- type this in terminal : python3 get-pip.py
- then to install numpy type: pip3 install numpy
- now to use any imported packages, we need to import them with: import numpy as np, to import entire numpy package
- to import specific function from numpy, we can do: from numpy import array

* NumPy arrays just contains one type

* Numpy array VS List example:
py_List = [1,2,3]
numpy_array = ([2,3,4])
py_List + py_List gives [1,2,3,2,3,4]
numpy_array + numpy_array gives ([3,5,7]), which is [(1+2), (2+3), (3+4)]
