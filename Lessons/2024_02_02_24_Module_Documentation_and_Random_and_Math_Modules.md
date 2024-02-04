# Python 2
Friday, February 2nd 2024

### Module Documentation and Exploring the Random & Math Modules

**AIMS:** 
* What is the Python module index and how can we leverage it to support our work as we code and develop ourselves as programmers?
* In what ways can we use the `random` and `math` modules in our programs?

**OUTCOME ALIGNMENT:**

<ins>IEC.TYS64T.6</ins>: Write and analyze programs and code segments that utilize built-in and user defined modules and packages.
<br><ins>IEC.TYS64T.7</ins>: Model employability skills such as personal mindset, planning for success, and collaboration.

**SUCCESS CRITERIA:**

- [ ] I can use the `dir()` function to display the list of a module's entities.
- [ ] I can use the Python module index as a resource in determining how to implement a module's entities.
- [ ] I can implement a variety of entities from the `random` and `math` modules in my programs.

**DO NOW:** Create a new file named `module_practice.py` in the Python_2 subdirectory of your Computer Science Portfolio on your virtual machine and copy/paste the code below:

```python
import random
print(dir(random))
```
Save, run, and observe the output of your program.

Next, delete the import statement.  

Save, run, and observe the output of your program again.

**Turn & Talk:** 
* What did you observe the first time you ran your program?  What do you think the data displayed in the terminal represents?
* What did you observe the second time you ran your program?  Based on your observation, what might you be required to do before calling the `dir()` function?

**AGENDA:**

1. The `dir()` Function.
2. The Python Module Index
3. The `Random` Module
4. The `Math` Module
5. Head Start on Homework

**HOMEWORK:** Lab02 - Random Math


**As you work, remember to...**
<br>...import all neccessary modules and/or entities from modules.
<br>...refer to the <a href = 'https://docs.python.org/3/library/random.html'>random module reference page.</a>
<br>...refer to the <a href='https://docs.python.org/3/library/math.html'>math module reference page</a>. 
<br>...run frequently to test.
<br>...troubleshoot as needed.
<br>...regularly save, commit, and push to GitHub.
<br>...include appropriate commit messages.

**PART A:**

1. Create a new file named `LastNameFirstInitial_Lab02_Random_Math.py` in the Python_2 subdirectory of your Computer Science Portfolio on your virtual machine.
2. Open GitBash
3. Change the directory to the Python_2 subdirectory of your Computer Science Portfolio.
4. Start tracking `LastNameFirstInitial_Lab02_Random_Math.py` by entering the following command:
```
git add LastNameFirstInitial_Lab02_Random_Math.py
```
5. Code the following functions:

* `fact()` - This function should calculate the factorial of a natural number as described below: 
	* First, the function should prompt the user to select whether they prefer to choose the number or whether they prefer to have the program randomly choose the number.
  * If the user selects to choose, the function should prompt them to input a natural number between 1 and 10 (exclusive), and assign it to the variable, n.
  * Otherwise, the function should generate a random integer between 1 and 10 (exclusive) and assign it to the variable, `n`.
  * Next, the function should calculuate the factorial of `n`, and assign it to an appropriately named variable.
  * Finally the function should display the factorial of `n`.
<br><br>

* `ceil_floor_trunc()` - This function should calculate the ceiling, floor, and truncated version of a decimal number as described below:
	* First, the function should prompt the user to select whether they prefer to choose the number or whether they prefer to have the program randomly choose the number.
  * If the user selects to choose, the function should prompt them to input a decimal number between -10 and 10 (inclusive), and assign it to the variable, `x`.
  * Otherwise, the function should generate a random float between -10 and 10 (inclusive) and assign it to the variable, `x`.
  * Next, the function should calculuate the ceiling, floor, and truncated version of `x`, and assign each value to an appropriately named variable.
  * Finally the function should display the ceiling, floor, and truncated version of `x`.
<br><br>

* `power()` - This function should calculate the value of a number (integer or decimal) raised to an integer exponent as described below:
	*  First, the function should prompt the user to select whether they prefer to choose the base and exponent or whether they prefer to have the program randomly choose the base and exponent.
  *  If the user selects to choose, the function should prompt them to input any number (integer or decimal) between -10 and 10 (inclusive) for the base, any integer between -10 and 10 (inclusive) for the exponent, and assign them to the variables, `base` and `exponent` respectively.
  *  Otherwise, the function should generate a random float between -10 and 10 (inclusive) for the base, a random integer between -10 and 10 (inclusive) for the exponent, and assign them to the variables, `base` and `exponent` respectively.
  *  Next, the function should calculate the value of `base` ^ `exponent` and assign it to an appropriately named variable.
  *  Finally, the function should display the value of `base` ^ `exponent`.
<br><br>

* `lcm_gcd()` - This function should calculate the least common multiple and greatest common divisor of a pair of natural numbers as described below:
  * First this function should prompt the user to select whether they prefer to choose the numbers or whether they prefer to have the program randomly choose the numbers.
  * If the user selects to choose, the function should prompt them to input two natural numbers between 1 and 25 (exclusive) and assign them to the variables, `n` and `m`.
  * Otherwise, the function should generate two random integers between 1 and 25 (exclusive), and assign them to the variables, `n` and `m`.
  * Next, the function should calculate the least common multiple and greatest common divisor of `n` and `m`, and assign them to appropriately named variables.  Finally, the function should display the least common multiple and greatest common divisor of `n` and `m`.
<br><br>

* `hypotenuse()` - This function should calculate the length of the hypotenuse of a right triangle given the lengths of its legs as described below:
	* First, the function should prompt the user to select whether they prefer to choose the lengths of the legs or whether they prefer to have the program randomly choose the lengths of the legs.
  * If the user selects to choose, the function should prompt them to input any two lengths (integer or decimal) between 1 and 10 (inclusive) and assign them to the variables, `a` and `b`.
  * Otherwise, the function should generate two random floats between 1 and 10 (inclusive) and assign them to the variables, `a` and `b`.
  * Next the function should calculate the length of the hypotenuse and assign it to an appropriately named variable.
  * Finally, the function should display the length of the hypotenuse.
<br><br>

* `circle()` - This function should calculate the circumference and area of a circle given its radius as described below:
	* First, the function should prompt the user to select whether they would prefer to choose the radius or whether they would prefer to have the program randomly choose the radius.
  * If the user selects to choose, the function should prompt them to input any number (integer or decimal) between 1 and 10 (inclusive) and assign it to the variable, `r`.
  * Otherwise, the function should generate a random float between 1 and 10 (inclusive) and assign it to the variable, `r`.
  * Next, the function should calculate the circumference and area of a circle with radius, `r`, and assign them to appropriately named variables.
  * Finally, the function should display the circumference and area.

	<br>***Hints:***
	<br>*Circle Circumference Formula: C = 2 x pi x radius.*
	<br>*Circle Area Formula: C = pi x radius^2.*
<br>

* `random_element()` - This function should display a randomly selected element of a list as described below:
	* First, the function should generate an appropriately named empty list that will eventually be filled with elements related to a common theme (e.g. colors, sports, etc.).
  * Next, the function should fill the list by prompting the user to enter ten elements, one at a time, appending each to the list after it is input by the user (***Hint:** Consider using a for loop.*).
  * Finally, the function should display one random element from the list.
<br><br>

* `random_sub_list()` - This function should display a sub-list containing five randomly selected elements of a list as described below:
	* First, the function should generate an appropriately named empty list that will eventually be filled with elements related to a common theme (e.g. colors, sports, etc.).
  * Next, the function should fill the list by prompting the user to enter ten elements, one at a time, appending each to the list after it is input by the user (***Hint:** Consider using a for loop.*)
  * Finally, the function should display a random sub-list containing five elements from the list.

6. Save, commit, and push your program to GitHub.  Remember to include an appropriate commit message.

**PART B:**
1. Expand your program by coding it to...
* ...welcome the user.
* ...display the following text:
> Enter 1 to calculate the factorial of a natural number.
> <br> Enter 2 to calculate the ceiling, floor, and truncated version of a decimal number.
> <br> Enter 3 to calculate the value of an exponential expression.
> <br> Enter 4 to calculate a least common multiple and greatest common divisor of a pair of natural numbers.
> <br> Enter 5 to calculate the length of the hypotenuse of a right triangle.
> <br> Enter 6 to calculate the circumference and area of a circle.
> <br> Enter 7 to display a randomly selected element of a list.
> <br> Enter 8 to display a sub-list containing five randomly selected elements of a list.

* ...accept the user's response and assign it to an appropriately named variable. 
* ...call the appropriate function based on the user's response (***Hint:** Consider using a conditional.*).
* ...thank the user.

2. Save, commit, and push your program to GitHub.  Remember to include an appropriate commit message.

**PART C:**
1. Copy/paste the code below to the bottom of your file.
2. Respond to each reflection question/prompt within a comment.
3. Commit and push your file to GitHub (including the message, 'Updated lab (reflection).')

```python
# Reflection Questions:

# 1. What command can you write within a program to display the list of entities within a module?  What command must be executed first?

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 2. What resource can you use to learn more about the entities within a module?  

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 3. Provide an example of a number, x, such that floor(x) = trunc(x).  Provide an example of a number, x, such that floor(x) != trunc(x)

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 4. Find and name a function that can be used to determine whether a given value is or is not a number.  What module is it an entity of?

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 5. Explain the difference between "random" and "pseudorandom".  What type of random numbers does the random module produce, random or pseudorandom?

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 6. What is a seed, and what role does it play in generating pseudorandom numbers?

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 7. Why does the following code generate the same sequence of random numbers every time it is run?

#
# import random
# random.seed(1)
# print(random.random())
# print(random.random())
# print(random.random())
#

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 8. Explain the difference between the randint() and the randrange() functions of the random module.

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 9. Explain the difference between the choice() and the sample() functions of the random module.

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 10. Find and name a function that can be used to rearrange the elements of a list in a random order.  What module is it an entity of?

# REPLACE THIS TEXT WITH YOUR RESPONSE.
```


##
**REFERENCE:**

**<a href='https://docs.python.org/3/py-modindex.html'>Click here for the Python module index.</a>
<br><br><a href = 'https://docs.python.org/3/library/random.html'>Click here for the random module reference page</a>
<br><br><a href='https://docs.python.org/3/library/math.html'>Click here for the math module reference page</a>**

|To...|Code...|
|---|---|
|...display all entities in a module.<br><br>Note: The module must first be imported.|`dir(module_name)`|
<br>

**Sample Entities from the random module.  See the <a href = 'https://docs.python.org/3/library/random.html'>random module reference page</a> for full list of entities.**

|To...|Code...|
|---|---|
|...generate a random float between 0 and 1 (inclusive).|`random()`|
|...generate a random float between `a` and `b` (inclusive).|`uniform(a,b)`|
|...generate a random integer between `a` and `b` (inclusive).|`randint(a,b)`|
|...generate a random integer between `a` and `b` (exclusive).|`randrange(a,b)`|
|...select a random element from a sequence (e.g. a list, string, etc.).|`choice(sequence_name)`|
|...select a random subset of a sequence (e.g. a list, string, etc.).|`sample(sequence_name)`|
|...set the initial seed used to generate pseudorandom values.|`seed()`|
<br>

**Sample entities from the math module.  See the <a href='https://docs.python.org/3/library/math.html'>math module reference page</a> for a full list of entities.**

|To...|Code...|
|---|---|
|...determine the factorial of `n`. (i.e.`n` x `n-1` x `n-2` x...x `1`)|`factorial(n)`|
|...determine the ceiling of `x`. (i.e. round up)|`ceil(x)`|
|...determine the floor of a `x`. (i.e. round down)|`floor(x)`|
|...determine the truncated version `x`. (i.e. the whole number part of a decimal number)|`trunc(x)`|
|...determine the value of `a`^`b`|`pow(a,b)`|
|...determine the least common multipe of `a` and `b`|`lcm(a,b)`|
|...determine the greatest common divisor of `a` and `b`|`gcd(a,b)`|
|...determine the hypotenuse of a right triangle with legs of length `a` and `b`|`hypot(a,b)`|
|The constant, pi (i.e. 3.141592...)|`pi`|


