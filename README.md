print("Hello, World!")
if 5 > 2:
    print("Five is greater than two!")
    
x = 5
y = "Hello, World!"

print(x)
print(y)

#Might as well include a comment

""" Here is some text 
that is still a comment even though it goes over several lines"""

x = "awesome"
print("Python is " + x)

import random

print(random.randrange(1, 10))

list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

list3 = list1 + list2
print(list3)


def my_function(food):
  for x in food:
    print(x)

fruits = ["apple", "banana", "cherry"]

my_function(fruits)

f = open("Test.txt", "rt")
print(f.read())


#Adding content to t a file

f = open("Test.txt", "a")
f.write("Now the file has more content!")
f.close()

#open and read the file after the appending:
f = open("Test.txt", "r")
print(f.read())

import numpy
import matplotlib.pyplot as plt

x = numpy.random.normal(5.0, 1.0, 1000)
y = numpy.random.normal(10.0, 2.0, 1000)

plt.scatter(x, y)
plt.show()
