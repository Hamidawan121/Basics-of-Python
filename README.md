# Basics-of-Python
Basics of python code for new birds
print("hello anaconda")
if 5>2:
      print("Five is greater than two")
      #I am learning python
      print("I am learning python")
# =============================================================================
# "Assignment Statement", Basis Assignment
# It creates and changes variables, This statement provides and 
#expression and name of a variable
# =============================================================================
shares= 150
price= 3+5.0/8.0
value= shares* price
print("value",value)

# =============================================================================
# Augmented Statement,To Create Augmented statement By adding any arithmatic 
# operator with the assignment operator
# =============================================================================
portfolio= 0
portfolio += 150*2+1/4.0
portfolio += 75*1+7/8.0
print("portfolio",portfolio)
# =============================================================================
# Genral Arithmatic Operators "PEMDAS", Paranthesis, Exponents, Multiplication, 
# Division, Addition, Substraction
# =============================================================================
print((2+2)*2/2+2-2)

# =============================================================================
# Assigning values to multiple variables
# =============================================================================
x, y, z = "Kiwi", "Grapes", "Banana"
print(x,y,z)

# =============================================================================
# Assigning same value to  multiple variables in a single line
# =============================================================================
x = y = z = "Apple"
print(x, y, z)
# =============================================================================
# additon of two integer variables
# =============================================================================
first_num = 10
second_num = 20
summation = first_num + second_num
print(summation)
print(first_num + second_num)
# =============================================================================
# Data Types
# =============================================================================
#String
string = "Python is interesting."
#Integer
x = 1 
#float
y = 2.8 
#complex
z = 1j 
#List []
thislist = ["apple", "banana", "cherry"] 
#tuple ()
thistuple = ("apple", "banana", "chery") 
print(thistuple[1])
#Mapping type, dictionary {}
thisdict ={
    "brand": "Ford",
    "model": "Mustang",
    "year": 1965
    }
print(thisdict)
#Set {}
thisset = {"apple", "banana", "cherry"}
#to add one item in set
thisset.add("orange")
#to add multiple item in set
thisset.update("mango", "kiwi", "peach")
#to know number of items in a set
print(len(thisset))
#to remove an item form set
thisset.remove("orange")
#frozenset "it could not be changed" ([])
cities =frozenset(["Lahore","Karachi","Islamabad"])
#Boolean type, "True", or "False"

# =============================================================================
# Import Date & Time
# =============================================================================
import datetime
now = datetime.now()
t = now.strftime("%H:%M:%S")
print("time:", t)
now = datetime.now()
t = now.strftime("%H:%M:%S")
print("time:", t)
# =============================================================================
# 
# ============================================================================
from datetime import datetime
now = datetime.now()
t = now.strftime("%A,%w,%b,%B,%m,%Y,%H:%M:%p")
print("time:", t)
# =============================================================================
# 
# =============================================================================
a=200
b=33
if b > a:
    print("b is greater than a")
elif a == b:
    print("a and b are eaual")
else:
    print("a is greater than b")
x = 0
if x > 10:
    print ("x is greater than 10")
if x > 20:
    print ("Also greater than 20")
if x > 30:
    print("Also greater than 30")
if x > 40:
    print("Also greater than 40")
else:
    print ("but less than 10")    
# =============================================================================
# 
# =============================================================================
fruits = ["Cherry", "Mango", "Fig", "Guava"]
for x in fruits:
    print(x)
# =============================================================================
# 
# =============================================================================
for x in range(6):
    print(x)
else: print("Done")
# =============================================================================
# 
# =============================================================================
for x in "banana":
    print(x)
# =============================================================================
# 
# =============================================================================
things = ["Pen", "Chair", "Table"]
col = ["Red", "Green", "Blue"]
for x in things:
    for y in col:
        print(y,x)
# =============================================================================
#         
# =============================================================================
i = 1
while i <10:
    print(i)
    i += 1
# =============================================================================
#     
# =============================================================================
fruits = ["apple", "banana", "cherry"]
for x in fruits:
    if x == "cherry":
            continue
    print(x)
# =============================================================================
#     
# =============================================================================
i = 0
while i < 6:
    i += 1
    if i == 2:
            continue
# =============================================================================
#     print(i)
# =============================================================================
fruits = ["apple", "banana", "cherry"]
for x in fruits:
    if x == "cherry":
            break
    print(x)
# =============================================================================
# General Arithmatic Operations
# =============================================================================
90//4
a = 2
b = 4
c = a**b
print(c)
2**100
65536/36
65536/18
65536/8
65536/32
# =============================================================================
# # Verification of statements with print function
# =============================================================================
a = 21
b = 10
c = 0
c = a + b
print ("value of c is ", c)
c = a - b
print ("value of c is ", c)
c = a * b
print ("value of c is ", c)
c = a / b
print ("value of c is ", c)
# =============================================================================
# Verification of statements with print function
# =============================================================================
f = 10
h = 12
print('f > h is' ,f>h)
print('f < h is' ,f<h)
print('f == h is' ,f==h)
print('f != h is' ,f!=h)
print('f >= h is' ,f>=h)
print('f <= h is' ,f<=h)

# =============================================================================
# Verification of statements about declared variables
# =============================================================================
f = 10
h = 12
f > 5 and f < h
f > h or f > 10
not (f > h and f < 0)
# =============================================================================
# 
# =============================================================================
x is y
x is not y
# =============================================================================
# Comparison of variables by &, |, ~, ^
# =============================================================================
a = 10
b = 4
print("a & b =", a & b)
print("a | b =", a | b)
print("~a  =", ~a)
print("a ^ b =", a ^ b)
# =============================================================================
# Last name could be fixed in the function
# =============================================================================
def my_function(fname):
    print(fname + "awan")
my_function("Hamid ")
my_function("Zahid ")
my_function("Nasir ")
# =============================================================================
# Define a function with first name and last name
# =============================================================================
def my_function(fname, lname):
    print(fname + " " + lname)
my_function("Hamid", "Awan")
# =============================================================================
# default setting in fucttion
# =============================================================================
def my_function(country = "Norway"):
    print("I am from "+ country)
my_function("Pakistan")
my_function("Sweden")
my_function()
my_function("KSA")
my_function("China")
# =============================================================================
# indexing in list of a function
# =============================================================================
def my_function(*kids):
    print("the youngest child is " + kids[2])
my_function("Usman", "Maryam","Aiza")
# =============================================================================
# print list in a function
# =============================================================================
def my_function(food):
    for x in food:
        print(x)
fruits =["apple", "banana", "Cherry"]
my_function(fruits)
# =============================================================================
# Recursion
# =============================================================================
def tri_recursion(k):
    if(k > 0):
            result = k + tri_recursion(k - 1)
    else:
        result = 0
    return result
print("\n\nRecursion Example Results")
tri_recursion(3)
# =============================================================================
# Type , sorting, power
# =============================================================================
type("Hamid Awan")

foods = ["Mango","Cherry","Tomato"]
print(sorted(foods))

pow(5,5)
# =============================================================================
# lambda fuction
# =============================================================================
x = lambda a: a + 10
print(x(5))

x = lambda a, b: a * b
print(x(5,10))

x = lambda a, b, c: a + b + c
print(x(5, 6, 2))

def myfunc(n):
    return lambda a : a * n
mydoubler = myfunc(2)
print(mydoubler(11))

def myfunc(n):
    return lambda a : a * n
mytripler = myfunc(3)
print(mytripler(11))

# =============================================================================
# Try and except function
# =============================================================================
my_numbers = [1,2,3,4]
try:
    my_numbers[4]
except IndexError:
    print('The index you used is invalid.')
    
print('The code executed')
# =============================================================================
# Assertion
# =============================================================================
def check_type(year):
    try:
        assert type(year) == int
    except AssertionError:
        print('The type of year is invalid')
        return False
    return True
print (check_type(year=2021.20))
# =============================================================================
# Create a class & object
# =============================================================================
class MyClass:
    x = 10
print(MyClass)
# =============================================================================
# Self Parameter - init fuction
# =============================================================================
class Person:
        def __init__(self, name, age):
            self.name = name
            self.age = age
p1 = Person("Hamid", 40)
print(p1.name)
print(p1.age)
# =============================================================================
# slef parameter could be replaced by myobject or any other word
# =============================================================================
class Person:
        def __init__(myobject, name, age):
            myobject.name = name
            myobject.age = age
p1 = Person("Hamid", 40)
print(p1.name)
print(p1.age)
# =============================================================================
# A fuction could also be defined in a object "Object Methods"
# =============================================================================
class Person:
        def __init__(myobject, name, age):
            myobject.name = name
            myobject.age = age
        def myfunc(xyz):
            print("Hi My Name is " + xyz.name, xyz.age,)
p1 = Person("Hamid", 40)
p1.myfunc()
# =============================================================================
# Modifying object properties
# =============================================================================
class Person:
        def __init__(myobject, name, age):
            myobject.name = name
            myobject.age = age
        def myfunc(xyz):
            print("Hi My Name is " + xyz.name, xyz.age,)
p1 = Person("Hamid", 40)
p1.age = 42
p1.myfunc()
# =============================================================================
# Deleting Object Properties
# =============================================================================
class Person:
        def __init__(myobject, name, age):
            myobject.name = name
            myobject.age = age
        def myfunc(xyz):
            print("Hi My Name is " + xyz.name, xyz.age)
p1 = Person("Hamid", 40)
del p1.age
p1.myfunc() # output AttributeError: 'Person' object has no attribute 'age'

# =============================================================================
# Deleting an object
# =============================================================================
class Person:
        def __init__(myobject, name, age):
            myobject.name = name
            myobject.age = age
        def myfunc(xyz):
            print("Hi My Name is " + xyz.name)
p1 = Person("Hamid", 40)
del p1
#print(p1) #output NameError: name 'p1' is not defined


# =============================================================================
# Creating a child class
# =============================================================================
class Person:
    def __init__(self, fname, lname):
        self.firstname = fname
        self.lastname = lname
    def printname(self):
        print(self.firstname, self.lastname)
        
class Student(Person):
    pass
    
x = Student("Hamid", "Awan")
x.printname()
# =============================================================================
# Add __init__() function in child class
# =============================================================================
class Person:
    def __init__(self, fname, lname):
        self.firstname = fname
        self.lastname = lname
    def printname(self):
        print(self.firstname, self.lastname)
        
class Student(Person):
    def __init__(self, fname, lname):
       Person.__init__(self, fname, lname) 
        
x = Student("Hamid", "Awan")
x.printname()
# =============================================================================
# Super Function
# =============================================================================
class Person:
    def __init__(self, fname, lname):
        self.firstname = fname
        self.lastname = lname
    def printname(self):
        print(self.firstname, self.lastname)
        
class Student(Person):
    def __init__(self, fname, lname):
       super().__init__(fname, lname) 
        
x = Student("Hamid", "Awan")
x.printname()

# =============================================================================
# Adding properties in a class
# =============================================================================
class Person:
    def __init__(self, fname, lname):
        self.firstname = fname
        self.lastname = lname
    def printname(self):
        print(self.firstname, self.lastname)
        
class Student(Person):
    def __init__(self, fname, lname):
       super().__init__(fname, lname)
       self.graduationyear = 2000
        
x = Student("Hamid", "Awan")
print(x.graduationyear)
x.printname()
# =============================================================================
# Adding Methods in a class
# =============================================================================
class Person:
    def __init__(self, fname, lname):
        self.firstname = fname
        self.lastname = lname
    def printname(self):
        print(self.firstname, self.lastname)
        
class Student(Person):
    def __init__(self, fname, lname, year):
       super().__init__(fname, lname)
       self.graduationyear = 2000
    def welcome(self):
        print("Welcome", self.firstname, self.lastname, "to the class of", self.graduationyear)
        
x = Student("Hamid", "Awan", 2000)
x.welcome()
# =============================================================================
# Example of inheritence
# =============================================================================
class Fruit:
     
     """
     A class is defined for fruits,
     to create objects of this class.
     """
     
def __init__(self, name, nutrients):
     try:
             assert type(nutrients) == list
     except AssertionError:
             print('invalid construction')
             raise Exception     
     self.name = name
     self.nutrients = nutrients
     self.is_ripe = False
def get_name(self):
    return self.name
def get_nutrients (self):
    print(self.name + ' has following nutrients:')
    for value in self.nutrients:
        print (value)
def check_ripeness(self):
    return self.is_ripe
def ripe_fruit(self):
      self.is_ripe = True
# End of Fruit Class

class Citrus(Fruit):
        def __init__(self, name, nutrients):
            super().__init__( name,nutrients)
            self.type='Citrus'
            self.characteristic = 'Pulpy and Juicy'
        def get_type(self):
            return self.type
# End of Citrus Class

Orange = Citrus(name='Orange', nutrients=['vitamin D','vitamin C']) 
Orange.get_nutrients()
           
# =============================================================================
# # Example of class inheritence
# =============================================================================
from typing import List

class Fruit:
    """
    A class is defined for fruits,
    to create objects of this class.
    """

    def __init__(self, name: str, nutrients: List[str]):
        if not isinstance(nutrients, list):
            raise TypeError('nutrients argument must be a list')
        self.name = name
        self.nutrients = nutrients
        self._is_ripe = False

    @property
    def is_ripe(self) -> bool:
        return self._is_ripe

    def get_name(self) -> str:
        return self.name

    def get_nutrients(self) -> None:
        print(f'{self.name} has the following nutrients:')
        for nutrient in self.nutrients:
            print(nutrient)

    def ripe_fruit(self) -> None:
        self._is_ripe = True

class Citrus(Fruit):
    def __init__(self, name: str, nutrients: List[str]):
        super().__init__(name, nutrients)
        self.type = 'Citrus'
        self.characteristic = 'Pulpy and Juicy'

    def get_type(self) -> str:
        return self.type

if __name__ == '__main__':
    Orange = Citrus(name='Orange', nutrients=['vitamin D', 'vitamin C']) 
    Orange.get_nutrients()
# =============================================================================
# File Handling
# =============================================================================
f = open("demofile.py", "r")
print(f.read())
# =============================================================================
# Create , Open a file,  x = "make an empty file", r = "read the file"
# =============================================================================
f = open("demofile.txt", "x")
f = open("demofile.txt", "r")
print(f.read())

f = open("demofile.py", "r")
print(f.read())
# =============================================================================
# Read only parts of the file (read only 5 letter from file)
# =============================================================================
f = open("demofile.txt","r")
print(f.read(5))
# =============================================================================
# Read line
# =============================================================================
f = open("demofile.txt","r")
print(f.readline())
# =============================================================================
# read file liny by line, loop will be used
# =============================================================================
f = open("demofile.txt","r")
for x in f:
    print(x)
f.close()
# =============================================================================
# Write to an existing file
# =============================================================================
f = open("demofile.txt","a")
f.write(" Good Learning and earning demands hardwork and patience ")
f.close()
f = open("demofile.txt","r")
print(f.read())
# =============================================================================
# Overwrite the already written content
# =============================================================================
f=open("demofile.txt","w")
f.write("I have deleted all content!")
f.close()
f=open("demofile.txt","r")
print(f.read())
# =============================================================================
# # Overwrite the already written content
# =============================================================================
f = open("demofile.txt","w")
f.write("Momo and ayzi are very naughty girls")
f.close()
f=open("demofile.txt","r")
print(f.read())
# =============================================================================
# Delete a file
# ==========================================================================
import os
if os.path.exists("Trial.txt"):
   os.remove("Trial.txt")
   print("File Deleted")
else:
    print("The file does not exist")
# =============================================================================
# To Delete a Folder
# =============================================================================
import os
os.rmdir("New Folder")
print("Folder Deleted")
# =============================================================================
# Create a  new folder, Create a file in that new folder, write / read in it
# =============================================================================
import os
os.makedirs("My Folder2")
print("New Folder Made")
f = open("My Folder2/demofile.txt", "x")
f = open("My Folder2/Demofile.txt", "a")
f.write("This is a new file")
f.close()
f = open("My Folder2/demofile.txt", "r")
print(f.read())
print("No error in this code")
# =============================================================================
# Read CSV and LXML Files
# =============================================================================
import csv
with open('employee.txt','w', newline='') as file:
    writer = csv.writer(file)
    writer.writerow(["name", "department", "DOB", "month"])
    writer.writerow(["Alex", "Police", "17-07-1987", "July"])
    writer.writerow(["Monti", "Education", "17-06-1986", "June"])

# =============================================================================
# CSV files reader, Use of CSV.reader()     
# =============================================================================
import csv
with open('employee.txt') as csv_file:
    csv_reader = csv.reader(csv_file, delimiter=',')
    line_count = 0
    for row in csv_reader:
            if line_count == 0:
                print(f'Column names are {",".join(row)}')
                line_count += 1
            else:
                print(f'\t{row[0]} works in the {row[1]} department, and was born in {row[2]}.')
                line_count += 1
            print(f'Processessed {line_count} lines.')
# =============================================================================
# Download videwo using python (Additonal excercise)            
# =============================================================================
from pytube import YouTube
link = input("https://youtu.be/V2efVSXSlqc")
video = YouTube(link)
stream = video.streams.get_highest_resolution()
stream.download()

# =============================================================================
# XML Module
# =============================================================================
from lxml import etree
def parseBookXML(xmlFile):
    with open(xmlFile) as fobj:
        xml = fobj.read()
    root = etree.fromstring(xml)
    book_dict = {}
    books = []
    for book in root.getchildren():
        for elem in book.getchildren():
            if elem.text:
                text = elem.text
            else:
                text = ''
            if elem.tag == 'author':
                last_name, first_name = text.split(',')
                print(elem.tag + ':', first_name, last_name)
            else:
                print(elem.tag + ":"+ text)
            book_dict[elem.tag] = text
        if book.tag == "book":
            books.append(book_dict)
            book_dict = {}
    return books
    
    
my_books = parseBookXML("C:\\Users\\hamid.mehmood\\books.xml")
    
# =============================================================================
#    OS and Sub Process Module  
# =============================================================================
# Make a directory
import os
os.mkdir("C:\\Users\\hamid.mehmood\\TestFolder")

 # Changing the directory
os.chdir("C:\\users\\hamid.mehmood\\TestFolder")    
os.getcwd()
os.chdir("C:\\Users\\hamid.mehmood")
os.getcwd()
os.listdir("C:\\Users\\hamid.mehmood")
os.path.exists("C:\\Users\\hamid.mehmood")
os.path.join(args*)
os.path.split("C:\\users\\hamid.mehmood\\TestFolder")
os.path.isfile("C:\\users\\hamid.mehmood\\demofile.txt")
os.path.isdir("C:\\users\\hamid.mehmood\\")
os.listdir("C:\\users\\hamid.mehmood\\")
# =============================================================================
# =============================================================================
# Make a new Subprocess
# =============================================================================
import subprocess
subprocess.call(['dir'], shell= True)
output =subprocess.check_output(['dir'], shell= True)
# =============================================================================
# 
# =============================================================================
import subprocess
    output =subprocess.check_output(['dir'], shell= True)


