# Python 2
Monday, February 5th 2024

### Analyzing Code that Utilizes the Random and Math Modules

**AIM(S):** 
* In what ways can we leverage code tracing strategies to analyze code snippets that call on entities from the random and math modules?

**OUTCOME ALIGNMENT:**

<ins>IEC.TYS64T.2</ins> Apply basic programming concepts (e.g. control flow, data collections, functions, exception-handling) to more complex contexts.
<br><ins>IEC.TYS64T.6</ins>: Write and analyze programs and code segments that utilize built-in and user defined modules and packages.

**SUCCESS CRITERIA:**

- [ ] I can determine the result of executing code snippets that call on entities from the math and random modules.
- [ ] I am applying code tracing strategies correctly, consistently, and effectively.

**DO NOW:** Apply code tracing strategies to determine the result of executing the following code snippet:

```python
import math

result = math.pow(math.pi,1) == 1 
print(int((result))
```

Open your `module_practice.py` file from yesterday's lesson, enter the code above, save, and run, to confirm your response.

**Turn & Talk:** 
* What code structures were involved in the code snippet above?
* What code tracing strategies did you apply?
* What if any errrors, did you make, and what did you learn from them?

**AGENDA:**

1. Code Tracing
2. Code Snippets Involving the math Module
3. Code Snippets Involving the random Module
4. Practice
5. Share

**EXAMPLES:**

```python
#Example 1/ What is the expected result of executing the following code snippet?  If executing the code snippet will result in an error, explain why.

import math

result = ceil(-pow(math.pi,1)) != math.factorial(3) 
print(int(result))
```

```python
#Example 2/ What are the possible results when the following code segment is executed?  If executing the code snippet could result in an error, explain what could cause that error to occur and explain why.

from random import *

for i in range(random.randint(1,2))
	print(random.randrange(1,2))
```


**PRACTICE:**

1. On paper, use code tracing strategies to determine the output of each of the following code snippets.
2. Capture images of your code tracing work in a single pdf and save it in the Python_2 subdirectory of your Computer Science Portfolio on your virtual machine.
3. Title your pdf: `LastNameFirstInitial_Code_Tracing_Exercises_Math_and_Random.pdf` 

```python
#Exercise 1/ What is the expected result of executing the following code snippet?  If executing the code snippet will result in an error, explain why.

import math
result = math.gcd(9,12) == math.factorial(3)
print(result)
```

```python
#Exercise 2/ What is the expected result of executing the following code snippet?  If executing the code snippet will result in an error, explain why.

from math import *
result = math.floor(9/2) == 9//2
print(result)
```

```python
#Exercise 3/ What is the expected result of executing the following code snippet?  If executing the code snippet will result in an error, explain why.

from math import *
result = factorial(4) != lcm(8,12)
print(int(result))
```

```python
#Exercise 4/ What is the expected result of executing the following code snippet?  If executing the code snippet will result in an error, explain why.

import math
result = -math.pow(2,3) != math.floor(-8.5) 
print(int(result))
```

```python
#Exercise 5/ What is the expected result of executing the following code snippet?  If executing the code snippet will result in an error, explain why.

import math
result = math.lcm(3,9) == math.pow(math.trunc(pi),2)
print(int(result))
```

```python
#Exercise 6/ What is the expected result of executing the following code snippet?  If executing the code snippet will result in an error, explain why.

import math
result = factorial(gcd(8,12)) == ceil(3.5)
print(int(result))
```

```python
#Exercise 7/ What is the expected result of executing the following code snippet?  If executing the code snippet will result in an error, explain why.

from math import *
result = floor(6.25) != math.factorial(gcd(6,9)) 
print(result))
```

```python
#Exercise 8/ What are the possible results when the following code segment is executed?  If executing the code snippet could result in an error, explain what could cause that error to occur and explain why.

from random import *

for i in range(2):
	print(randrange(1,2), end ='')
```

```python
#Exercise 9/ What are the possible results when the following code segment is executed?  If executing the code snippet could result in an error, explain what could cause that error to occur and explain why.

import random

for i in range(3):
	print(random.randint(1,3), end ='')
```

```python
#Exercise 10/ What are the possible results when the following code segment is executed?  If executing the code snippet could result in an error, explain what could cause that error to occur and explain why.

from random import *

for i in range(10):
	print(random.randint(1,2), end ='')
```

```python
#Exercise 11/ What are the possible results when the following code segment is executed?  If executing the code snippet could result in an error, explain what could cause that error to occur and explain why.

import math
import random

for i in range(1):
	print(random.randrange(math.floor(2.5),math.ceiling(3.5)), end ='')
```

```python
#Exercise 12/ What are the possible results when the following code segment is executed?  If executing the code snippet could result in an error, explain what could cause that error to occur and explain why.

from math import *
from random import *

for i in range(2):
	print(randrange(pow(pi,0),trunc(2.5)), end ='')
```

**HOMEWORK:** 

Reading: https://edube.org > Sign In > Python Essentials 2 > 1.2.1.9 - 1.3.1.5

**Note:** If you have not successfully completed today's code analysis exercises, you must see Mr. Swotinsky at the end of the day for support.


##
**REFERENCE:**

|Code Tracing Strategies for Code Snippets Using Entities from `math` and `random`|
|---|
|1.  Take a moment to check the import command. If the module is imported as a whole (e.g. `import math`), remember to call entities using dot notation (e.g. `math.pow()`).  If individual (or all) entities have been imported (e.g.,`from math import pow` or `from math import *`), remember to call entities without using dot notation (e.g.,`pow()`).<br><br>2.Pay close attention to `=` vs. `==`. A single equals sign (`=`) is used to assign data to a variable.  A double equals sign (`==`) is part of a boolean statement.  For example, consider,`result = 2 == 3`.  The value of `2 == 3` is `False` which is assigned to the variable, `result`.<br><br>3. Pay close attention to `==` vs. `!=` as well.  `==` means 'equal to'. `!=` means 'not equal to'.  So, the value of `2 == 3` is `False`, but the value of `2 != 3` is `True`.<br><br>4. Use the <a href='https://docs.python.org/3/library/math.html'>math module reference page</a> and the <a href = 'https://docs.python.org/3/library/random.html'>random module reference page</a> as resources.<br><br>5.  Treat code tracing exercises like mathematical order of operations problems.  Simplify one part of the code snippet at a time, and rewrite the simplified version of the code snippet after each step, until you reach the final result.|
