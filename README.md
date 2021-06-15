------------------------------Basics Of Python------------------------------------------

Make a new file with file_name.py 
Py is the python extension

Basically to Print anything just use print without any header or extra

print("Hello World")

run->run to run
2

Like for drawing using these print statements just add multiple print statements to design a thing 

check draw shape
the order of the instruction is necessary ,the console is used to show the output
As python uses interpreter it executes instructions line-by-line in order 

3
check variable
Variables
a container contains the data

to assign a variable just
variable_name="variable data"
it is just storing plane text as it is a string
to concatenate string text we use +

so to change a variable you just have to change the main variable data it'll change everywhere in the program
variable can be changed anywhere , and the

To store a number you just need to
variable_name=numerical data
it'll store the number

To store a boolean operation just

variabel_name=True/False

So the basic type of data
number
string
boolean
number for whole or decimal both
Ex. std_marks=50.5
String for plain text
std_name="M.Usama"
Boolean for true/false
Is_male=True
4
check print styles
some string format styles also in variable.py
5
strings
we have red the print ex print("something")
But now just have a look on manipulating it more

like:
print("something \n new line")
check strings
to concatenate strings we use +
functions in strings can be used to manipulate the strings by calling it by .
print(name.(somefunction))
to use multi function one after one you can use
like name.upper().isupper()


another function len(variable name) used to check the lenght of the function inside the print like in file
to print the specific character variablename[location]
as index location starts from zero u can print a character as the string is in array form

to get the specific location for yourself use the index function
to replace a word or character use the replace function
name.replace ("old" , "new")

6
check numbers
so to print a simple whole or negative or decimal number just put it in print
print(number)
arithmetic operations can be performed as well as
print(number 1 +number 2)
can be use parantheses (2*2) + 44
mod % use to find remiander
to convert the number to string just use the str function as
print(str(variable name))

math functions can be performed
as to get a absolute value just use the abs function like
abs(num)

the function pow to find power like
pow(num,power)
the function max used to print the max value out of multiple parameteri numbers
max(num,num,num,num...)
similar to min to find min
min(num,num,num,num...)
to use other math function we need to import

for this
from math import*
to import every math file

like the functions floor and ceil are used to grab the lower relevant and higher relevant number
to find the sqrt just use the sqrt function sqrt(4) returns 2.0 floating numb return

there are bunch of math functions available on the internet
7
check input
to get the input from the user itll be
input("enter the name or whatever")
variablename=input("enter the name")

8
check a basic calculator
Let's use expertise to build a calculator
the simple input statements use the strings but if we want it to be the number we have to convert the input statement
like
so we have to exclusively convert that in int or float
as int(num1)+int(num2)
but for decimal number it should be
float(num1)

9
check mid libs game
Mad Libs Game
feeling blanks with random words
ezpz project

10
check list

a list is just a sort of structure that uses to store a large amount of data and keep tracking on them
a list syntax
Variable_name=[element 1 ,2,3]
like ex:Multi_type_data=["Name",32,False]

to print list enter the name of the list in print
to print specific element name[element location starting from 0]
to print all element after a location name[element location :]
to inversely print like to print 2nd last element name[-2]
or to print all values after a number to the end number

like
print(list_name[starting index:ending index])
remember the ending index data is excluding like it'll not be printed.
so you can change any of the value like the array as
list_name[2]=some data

11
check list functions
so as the list is valuable as it stores a large amount of data so there are some functions introduced
to manipulate,extend or get information from the list let's have a look
onelist.extend(secondlist)
this list will append the additional data to the first list
you can even add an individual item to the list using append function
listname.append(item),it'll be added to the last of the list as appending

So to add the value to the individual location to any index use
listname.insert(location,value)
so the value will be added to that index and so the remaining will be moved accordingly like it'll be pushed.

To remove a specific element from the list just use remove function
listname.remove(value)
it'll remove the specific value

to clear the whole list to clear it we use the clear function
listname.clear()

to remove the last element a famous function pop() is used
listname.pop()

to search for the specific value in the list you can use the function index like
listname.index(value)
it'll return the specifc index for the value if it is in the list
or return an error

We can also count the specifc value in the list that how many times it is appearing to check this use
listname.count(value)

Ok, no more trash like the C and Java you can simply use the sort function to sort anytype of array whetehr it is alphabetical or numericla
list_name.sort()
it'll sort the list

or to reverse the specific list , use function reverse
list_name.reverse()
it'll reverse the given list

you can also just copy the list data to another new list like
list_name=old_list.copy()



extra : https://www.edureka.co/blog/python-list-remove/#:~:text=Python%20del%20operator%3A&text=The%20del%20operator%20removes%20the,the%20item%20at%20that%20index.
list.pop() –
The simplest approach is to use list’s pop([i]) method which removes and returns an item present at the specified position in the list.
list.remove() –
This is another approach where the method remove(x) removes the first item from the list which matches the specified value.
Slicing –
To remove the first item we can use Slicing by obtaining a sublist containing all items of the list except the first one.
The del statement –
Using Del statement, we can remove an item from a list using its index.The difference compared to pop() method is, that this does not return the removed element.

12
Tuple is anther data structure in python similar to the list
let's see how to create it:
One of the best example of tuple is that x,y coordinate
Tuple is immutable means that we can't change and modify it
lets make a tuple in form of coordinates
name=(x,y)

element of the tuple can be accessed using index location i.e,
tuple_name[0]
but not element can be changed
you can add tuples in list


13

check functions
To build a normal function you just have to use the keyword def
def function_name():
    indented statements

The statements under function need to be indented means these statements must be indented as if the next statement
is starting from the start of the line it'll not be counted under function check file

function can be used to accept and utilize parameters as like other languages
def function(parameter 1, parameter 2.... or no parameter)
    statements

check function with return
simply to return a value from function we use the return statement as
return some value

it can be stored in a variable or directly be printed

14
check if else
if statements can also be used in the python as
if condition :
    statements

for multiple conditions
if condition1:
    statements
elif condition2:
    statements
else

for conditional statements you can use
and
or
not

15
check ad calc
so just making a simple calc

16
Dictionaries
Data structure in Python which allows us to store data in key-value pairs
So key refers to as pointer to the specific stored data.The things here is basically similar to an english dictory
where you can find out specific definition attached to a specific word.
Check Dict
SO the syntax of a dictionry is not difficult
Dictionary_name={
key:value,
key:value,
.
.
nkey
}

Note:Each Key must be unique ,Check file as example
Keys can be numbers or strings
To retrieve the def to the key ,there are many such definitions
like
print(dictionaryname[key])
print(dictionaryname.get(key,default value))

17

Check Whileloop
whileloop is a simple type of loop for conitnusoly executing statements based on the specific condition
loops breaks when condition doesn't meet
while condition:
    statement1
    statement2
    .
    .
    statementn

18
find primenumbers between specific range
Using WHile loop we performed operation to findout prime numbers between specific range

19
check for
A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).
for variable in strings/tuple etc:
    statement 1
    statement 2
    statement n

range function is used to get a range of values one by one store in the variable like
range(number)

for variable in range(number):
print(variable)

it will print the numbers from 0 to number-1

19
check 2d llist
we can add multiple lists as the list elements within the list so it can be reffered as nested lists
so to do this
listname=[
[listnested1],[listnested2]....]

to get the specific element it will be as print(listname[rowindex][columnindex])

you can also use the nested for loop to get the element from 2d lists check 2d list

20
the idea of translation is basically taken from the Giraffe Acadmy on Youtube
check chimp translation

we use a basic function with the parmeter to get the user written phrase and then use for loop
to get the each indvidual character and if vowel replace with m
after doing it print it again ,
the translator=translator+"m" basically adds the m character to translator variable
lets check

21
check comments
comments are basically the unexecutable line of instruction written just for explaining the specific purpose
to the user ,
one line code can be written as
# 1-line code or instructions

for multi line
'''
code
code
code

'''

the code will not execute it is just an instruction that enhances learnings

22
One of the important thing in python is the error handlind
it basically refers to the fact that there can be errors when running a program and it will stop the execution
of whole program even if there is just a simple small error
so to prevent this we can use try except
try:
block of code
except:
print error

it will get the error from try block if there is and then the except line will if print statement is writen than
whatever error is there the except block will run and the program continuous

but to be specific of the type of error we have

try:
block of codes
except errortype:
block

so it will only excute the the except block on the specific error occured
23
check reading files in read folder of file handling folder

to read the external file first to open the file
open("file location name","mode")
if the files are in same directory just put the name of the file

mode can be
r read
w write
a append
r+ read/write

so open the file and store it to the variable to perform various function
readline() to get the line and move cursor to the next line
readlines() to read all lines
readable() to check whether the file is readable or not and then return boolean

there are many more functions can be found over internet

so to close file , its just variablename.close()

24
check writing files in write folder of file handling folder
to write to the file first we need to open the file
open("filename","a") for append mode the data will be appended
open("filename","w") for write mode the data will be overwritten

write function is used to write the data

x.filevariable("Data")
25
CHeck using Module in Module folder
Modules are just the external python file using in another python file ,so everything related to that files
whether it is variable or function that is imported to new file
so you don't have to rewrite the stuff again

we uses import filename
then use any of the function or variable into the new file as
filename.function()

python modules are pretty useful and saves time, many times when to save time search interenet for the specific
module written by other person and import it to your file ,,,,
the all python pre modules are in the lib folder
the https://docs.python.org/3/py-modindex.html here you can find out a list of python modules

26
let's Talk about PIP
PIP is basically package manager that uses to install,manage , uninistall the modules and pretty useful
PIP is preinstalled with the latest version of python3

to check if pip installed
open cmd
write pip --version

if not installed ,there is a bunch of videos on youtube to get it install in your mac/windows
you can install external or 3rd party modules using pip its simple using pip command but some times you
have to manually install the module using various steps in pip

let's consider you have to get module for docx document to manage it in python there is an external module
when searched on google
pip install python-docx
it will install that legitmate python module using cmd

usually these type of modules after installing gets placed inside the libs>sits-packages folder
so to simply install it using install pip

to uninstall the module , one can simply use
pip unninstall modulename
pip unninstall python-docx

it will uninstall the module and deletes its folder, so nolonger b supported

27
check box and app in class
The popular topic classes/objects
classes are basically the datatypes and objects are the character the uses these functions to perform a specifci task

class classname :

    def __init__(self,var1,var2)
        self.var1=var1
        self.var2=var2
this is just example

to import it in other file lets just
from filename import classname
variable=classname(value1,value2) object named variable
print(variable.var1) it will print the value of var1 passed when object is created

28
check math mind game and quiz in class folder

simply created a simple mathmind quiz game using basic concepts of class/object


29
OK lets see inheritence
inheritence is basically to inherit the functionality of one class by another
the top is the parent and the class inherits is the child
so you don't have to write again the functions written in the parrent class
class child class(parent class) :
    functions

 it will inherit the functions from parent class

 there is also anoter concept function overridding occurs when both parent and child have same name
 and its useful , as when the same function needs to be called by the child the overriden function in the child is first
 executed but not the inherited function .So, the result will be accurate explained in the example file

 check inheritence folder in the class folder
 
