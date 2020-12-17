# Classes

A class in python abstract the logic pertaining to a single real-world parallel this way we can use classes to section thge logic we ned to perform a task.

```python

class MyClass:

	variable = "something"

	def __init__(self, name, age):
		self.name = name
		self.age = age
	
	def print_details():
		print("Name: " + self.name + ", Age: " + str(self.age))

```

This will define a class called `MyClass` this class has a constructor and a single mathod called `print_details`. These can be used as follows:

```python

me = MyClass("Lufter", 18)

me.print_details()

```

This will create an instance of `MyClass` with a name and age, and it will call the `print_details` method which will print `Name: Lufter, Age: 18`.


### Constructor

```python

def __init__(self, name, age):
	self.name = name
	self.age = age

```

The constructor is a method called upon instanciating a new instance of a class, and is used to set the initial state. These valies can then be accessed throughout the class.

A constructor must always be called `__init__` and be delared with the `self` attribute which referes to the class instance.


### Self

```python

self.name = name

```

`self` refers the instance of the class. To access instance variables we call `self.` followed by the variable name. This differenciates from other variables.


### Getter Methods

```python

def getVar():
	return self.var

```

A getter method is a holdover from other languages and a coding convention as a way of accessing the value of a variable within a class. Its sole purpose to return the variable.


### Setter Methods

```python

def setVar(var):
	self.var = var

```

A setter method is a holdover from other languages and a coding convention as a way of setting the value of a variable within a class. Its sole purpose to set the variable.