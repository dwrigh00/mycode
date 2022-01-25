Lab Objective
The objective of this lab is to view the available built-in methods for you to use with the dir() function while in the Python shell. Methods can be described using the help() function. This is a useful way to learn about what is possible with Python.

Procedure
Launch the python3 interpreter.

student@bchd:~$ python3

Let's practice using the dir() function.

>>> dir(str)

What has been returned to us is all of the methods that can be used to alter string (str) objects. Lets create a string object.

>>> x = "EthGIG01"

Run dir() function on our string x, the same output should be returned that we saw previously.

>>> dir(x)

Let's pick one, and learn about it, like lower(). Methods always trail the object using dot notation.

>>> x.lower()

Cool. Looks like it made every character lowercase. Sometimes, methods have help pages. Try the following command to reveal the help page for lower().

>>> help(x.lower)

Press q to quit the help page. Then try another method. The upper() method will make all characters uppercase.

>>> x.upper()

We can also 'chain' together methods. When we do, they are processed from left-to-right. The method startswith() expects a string argument, and returns a true or false value. The following line first converts the x string-object to lowercase, then returns True, because it startswith eth

>>> x.lower().startswith("eth")

Alta3's Office is in Hershey, PA, where there's lots of dairy farms, which means lots of tractors. Think of a tractor like an object that (can) have a specialty attachment, the hay bailer, which is like a method. After the hay bailer's job is complete, it passes the hay bail off to the second specialty attachment, the trailer, which is like a second method. The analogy works, in that these attachments can be mixed-and-matched (to a point).

Classic-Hershey-Pennsylvania-Tractor-Example

Everything in Python is an object. So, suppose we imagine a new python object, like a boat. Boat's don't have hay bailers. That is to say, methods are uniquely associated with an object's type. To explore the concept further, let's create a file-object called x that has the attributes of myfile.txt, in write-mode (as in, we want to write text to it). We'll study input/output later, for now, we want to focus on getting to methods available to an object.

>>> x = open("myfile.txt", "w")

Now run dir() on our fileobject

>>> dir(x)

Wow. These are a lot different than the methods associated with string-object. Let's read the help() page on the read() method.

>>> help(x.read)

Press q to quit the help page. Did you notice some methods are surrounded by underscores? Those are built in methods, and in Python 3, are no different than any other method (as in, in Python 2, they were kind of special...). Let's start to explore them as well. Start by making x an integer (int) object.

>>> x = 5

Run dir() on x

>>> dir(x)

Change the attribute of integer object x by using the __add__() function.

>>> x.__add__(6)

The result is 11... which is 5 + 6. In Python, the + sign has actually been mapped to use the __add__() method. The __le__() method is the > (less than) method. Try it out. The following expression is read, "Is x less-than 3?".

>>> x.__le__(3)

Hope methods are starting to make sense. To be clear, methods are different than functions. Functions are just repeating code blocks. Methods are repeating code blocks that are applied directly to an object, as in: object.method()

Exit the Python interpreter.

>>> exit()

You can check out the same documentation you saw with the help() from outside of a python environment using pydoc. Let's use pydoc to read about the open function.

student@bchd:~$ python3 -m pydoc open

Press q to quit.

Let's use pydoc to read about the time module.

student@bchd:~$ python3 -m pydoc time

Press q to quit.

Let's now look at the python 2.7+ (old version of python) help documents. Use pydoc to read about the time module.

student@bchd:~$ python -m pydoc time

Press q to quit.

Good job. Run this lab anytime you need to explore how to manipulate an object.
