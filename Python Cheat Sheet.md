# Python Cheat Sheet

### [[ Variable Assignment ]]

Assign variables with the '=' sign and a vaiable name.

```python

string_variable = "variable contents"

intVariable = 123

floatvariable = 1.23

bool_variable_ = True

```

Variables in python can take a multitide of data types including the simple [[ Datatypes | datatypes ]] above (string, integer, float, boolean). Find more information at [[ Variable Assignment ]].


### [[ Select Statements ]]

Select statements are used to make a diverting choice in your code, chosing to run or not run a particular section.

```python

if (condition):
	
	# Run this code
	
else:

	# Run this other code

```

An `if` statement will run the code in the first section if the `condition` is `True`, if the condition returns `False` the code in the `else` section will run.


### [[ Iteration Statements ]]

Iteration lets you repeat code multiple times depending on a condition. The most common type of iteration is a `for` loop.

```python

for i in range(10):
	
	# Repeat this code 10 times

```

This will iterate over the code once for each value in the `range`, in this case 10 times, and will store the current value of `range` in `i`. The value for `i` can then be used for operations in the code, though only inside the `for` loop.


### [[ Function Definitions ]]

A function allows you to segment code and apply it wherever necessary without the redundancy of rewriting it.

```python

def function_name(attribute):
	
	# Function code

```

The function above is called `function_name` and it has 1 attribute called `attribute` attached to it. To run this function I need to call `function_name(attribute)` and replace `attribute` with a variable I want to use within the function.


### [[ Classes ]]

A class in python abstract the logic pertaining to a single real-world parallel this way we can use classes to section thge logic we ned to perform a task.

```python

class MyClass:

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