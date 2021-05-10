# Python coding guidelines

Python coding standards are used not only to increse the readability of the code but also for cleaniness of the code.
PEP 8 coding guidelines should be followed in 
Here are few coding guidelines that needs to be followed while writing the python code - 

1. Naming conventions - 

		i. Functions and variables should be lowercase with underscore for more than one word.
		ii. Class name should start with Uppercase followed by lowercase and use underscore in case of more than one word.
		iii. Name of the variable or function should be descriptive to the specific task and generic variables should be avoided.

2. Variables containing values should be defined outside the function, this is done so as to increase the reusability of the code for similar problem statement.

3. Avoid creating multiple dataframes within the single function as it uses unnecessary memory.

4. Avoid iterating through dataframe for assigning column values in the dataframe.
