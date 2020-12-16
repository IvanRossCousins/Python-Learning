# Select Statements

Select statements are used to make a diverting choice in your code, chosing to run or not run a particular section.

### If Statement

```python

if (condition):
	
	# Run this code
	
else:

	# Run this other code

```

An `if` statement will run the code in the first section if the `condition` is `True`, if the condition returns `False` the code in the `else` section will run.


### Elif Statement

```python

if (condition):
	
	# Run this code

elif (other_condition):

	# Run this other code
	
else:

	# Run this other other code

```

`elif` statements allow you to add another level of selection to the `if` statement with another condition. It helps reduce the number of nested `if` statements.


### Nested If Statement

```python

if (condition):

	# Run some code
	
	if (secondaty_condition):
	
		# Then run this code

	else:

		# Or this other code

```

Nested statements allow you to seperate the logic of if statements into multiple levels instead of including all the logic for a single situation into a signle if statement.


### Conditions and Operators

Conditions in each statement can be combined using [[ Python Cheat Sheet#Operators | operators ]] as they return booleans.

```python

if (condition && other_condition):

	# Run some code

```