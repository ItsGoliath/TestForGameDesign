# TestForGameDesign

import sys
import pandas as pd
print(sys.version)

print("hello ai")

# for hashtag press alt + 3
# run selection
# first select the code and then shift + alt + e

#if you wnt to bring back your code press
# cmd + z

#numbers
3

5.5

3 + 2

4 * 2

if 9 > 3:
    print("nine is greater than three")

type(3) #integer
type(100) #integer
type(5.5) #float
#type(5,5) # type error, not working

print("kemal")
type("kemal")

# comments can be used to explain phyton code
#comments can be used to make the code more readable
# comments can be used to prevent when testing code

print("hello world!")

#if you want to add a multi-line comments to your script, you can do so with """ triple quotes.

def multiplication(x,y):
    """

    :param x:
    :param y:
    :return:
    """
    print(x*y)

multiplication(2,3)

def kemal(x,y):
    """
    yorum satırı toplu
    """
    print(x+y)

kemal(50,60)

# pyhton variables
## variables are used to store data values.

# creating variables
## a variable is created the first time you assign a value to a variable

var1 = 5
var2 = 3

print(var1)
print(var2)

print(var1*var2)

# variables can change type after they are set and are not required to be stated with a certain type.
## Example
x = 9 # x type of int
type(x)

x = "Ahmet" #x type of string
print(type(x))

x = str(3)
print(type(x))

x = int(5.5) # x will be integer
print(type(x))


x = float(3) # x will be float
print(type(x))

# get type
# you can get the data type of a variable with the type() function

x = 3
y = "apple"
print(type(x))
print(type(y))

# you can use single or double quotes

z = "bekir"
t = 'bekir'

#they are same thing

#case sensitive

a = 3
A = "pink"

print(a)
print(A)

#they are different

myvar = "kemal"
my_var = "kemal"
_my_var = "kemal"
myVar = "kemal"
MYVAR = "kemal"
myvar2 = "kemal"

# give a short name or a more descriptive name
# variable name must start with a letter or the underscore character
# a variable name cannot start with a number

# not assign, or used
"""
2myvar = "kemal"
mv-var = "kemal"
my var = "kemal"
"""

# one value to multiple variables
x = y = z = "cat"
print(x)
print(y)
print(z)

# unpack collection

fruits = ["apple", "banana" , "orange"]
x,y,z = fruits
print(x , y , z)

# you can also use the + operator to output multiple variables
x = "phyton "
y = "is "
z = "great"
print(x + y + z)

x  = 5
y = 10
print(x + y)

x  = 10
y = "kemal"
#print(x + y) we get error

x = str(10)
y = " kemal"
print(x + y)

#Global Variables
x = "awesome"

def myFunc():
    print("pyhton is " + x)

myFunc()

# if you create a variable with the same name  inside a function this variable will be local
# can be used inside the function gloable variable with the same name will remain as it was
# global and with the original value

x = "awesome"

def myFunc():
    x = "fantastic"
    print("pyhton is " + x)
# output will be pyhton is fantastic
myFunc()

def myFunc():
    global x
    x = "fantastic"
myFunc()

print("phyton is " + x)

