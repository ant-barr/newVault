python variables
	variables are containers for storing data values
- python has no command for declaring a variable
- a variable is created the moment you first assign a value to it.

example:
	x = 5
	y = "john"
	print(x)
	print(y)
	this will output the stored values.

variables do not need to be declared with any particular type, and can even change type after they have been set.

example:
	x = 4   # x is of type int
	x = "sally"   # x is now of type str
	print(x)

Casting:
	if you want to specify the data type of a variable, this can be done with casting.

example:
	x = str(3)    # x will be '3'
	y = int(3)   # y will be 3
	z = float(3)   # z will be 3.0

Get the type
	you can get the data type of a variable with the type() function

example:
	 x = 5 
	 y = "john"
	 print(type(x))
	 print(type(y))
	 this will print out the type for x and y, being int and str respectively

single or double quotes?
	string variables can be declared either by using single or double quotes

example:
	x = "john"
	#  is the same as
	x = 'john'

Case-sensitive
	variable names are case sensitive

example:
this will create two variables:
	a = 4
	A = "sally"
	# A will not overwrite a

[[Python overview]]