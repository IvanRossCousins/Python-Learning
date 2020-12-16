# Iteration Statements

Iteration lets you repeat code multiple times depending on a condition.

### For Loops

```python

for i in range(10):
	
	# Repeat this code 10 times

```

This will iterate over the code once for each value in the `range`, in this case 10 times, and will store the current value of `range` in `i`. The value for `i` can then be used for operations in the code, though only inside the `for` loop.


### While Loops

```python

while (condition):
	
	# Repeat this code while condition is true

```

While loops repeat the code they contain so long as the condition is `True`. As soon as the condition is `False` the loop exits, if the condition is `False` when the code reaches the loop it will be skipped and never run.


### Break

```python

while (True):
	
	break

```

When a `break` is reached in a loop it immediately exits the loop.