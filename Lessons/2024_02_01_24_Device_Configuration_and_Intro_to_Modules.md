# Python 2
Thursday, February 1st 2024

### Device Configuration and Introduction to Modules

**AIMS:** 
<br>What tasks must we complete to configure our devices for Python 2?
<br>What are modules, and how can we leverage them to organize the programs we write?

**OUTCOME ALIGNMENT:**

<ins>IEC.TYS64T.6</ins>: Write and analyze programs and code segments that utilize built-in and user defined modules and packages.
<br><ins>IEC.TYS64T.7</ins>: Model employability skills such as personal mindset, planning for success, and collaboration.

**SUCCESS CRITERIA:**

**Device Configuration:**
- [ ] I have created a new repo on GitHub named `Computer_Science_Portfolio`.
- [ ] I have shared my `Computer_Science_Portfolio` repo with Mr. Swotinsky.
- [ ] I have installed Git on my virtual machine.
- [ ] I have cloned my `Computer_Science_Portfolio` repo to my virtual machine.
- [ ] I have created a subdirectory named `Python_2` within my `Computer_Science_Portfolio` repo on my virtual machine.
- [ ] I have successfully added, committed, and pushed my random lab to GitHub.

**Introduction to Modules:**
- [ ] I am able to describe what modules are and how they are used to organize programs.
- [ ] I am able to import modules and their entities for use in my programs.
- [ ] I am able to alias modules and their entities.
- [ ] I am able to call on entities from modules that I have imported.
- [ ] I am able to describe what a program's namespace is as well as how the concept of namespace relates to the importance of making strategic decisions about module imports.

**DO NOW:** Create and share a new repo: 

*When you are ready to show off your work, this repo will serve as your public-facing Computer Science Portfolio.*

**To create your new repo:**  

1. Navigate to your GitHub profile (github.com/YourUserName)
2. Click <ins>Repositories</ins>.
3. Click <ins>New</ins>.
4. Name your repository, **Computer_Science_Portfolio**.
5. For now, your repository does not need a description.
6. Set your repository to **Private**.  
7. Select **Add a README file**.
8. Leave the .gitignore template set to **None**.
9. Select a **Creative Commons Zero v1.0 Universal** license.
10. Click <ins> Create repository</ins>.

**To share your new repo:**

1. Click <ins>Settings</ins>.
2. Click <ins>Collaborators</ins>. (You may be prompted to sign in to GitHub again.)
3. Click <ins>Add people</ins>.
4. Add jswotinsky@schools.nyc.gov.

**AGENDA:**

1. Syllabus Review
2. Configuration Tasks (see reference section below.)
3. Introduction to Modules
4. Random Lab

**RANDOM LAB:**

**PART A:**
1. Open the the test file you created as part of device configuration task 4.
2. Write a line of code to import the full `random` module.
3. Write a short program that prompts the user to enter two integers and displays a random integer that is between the two integers input by the user.

*Hint: the `randint(a,b)` function from the `random` module returns a random integer between a and b.* 

4. Run your program to test, troubleshoot as needed, and save.
5. Commit and push your file to GitHub (including the message, 'Uploaded lab (full module import).')

**PART B:**
1. Modify your import command to import only the `randint(a,b)` entity from the `random` module.
2. Modify the rest of your code to make it work with your modified import command.
3. Run your program to test, troubleshoot as needed, and save.
4. Commit and push your file to GitHub (including the message, 'Updated lab (import one entity).')

**PART C:**
1. Modify your import command to import both the `randint(a,b)` and the `choice(x)` entities from the `random` module.
2. Expand your program by coding it to first prompt the user to enter a string, and then to display a random character from the string input by the user.

*Hint: the `choice(x)` function from the `random` module returns a random element from a sequence (e.g. a random character from string, a random element from a list, etc.).*

4. Run your program to test, troubleshoot as needed, and save.
5. Commit and push your file to GitHub (including the message, 'Updated lab (import two entities).')

**PART D:**
1. Modify your import command to import all entities from the `random` module.
2. Run your program to test, troubleshoot as needed, and save.
5. Commit and push your file to GitHub (including the message, 'Updated lab (import two entities).')

**PART E:**
1. Modify your import command to import both the `randint(a,b)` and the `choice(x)` entities from the `random` module, but this time use the following aliases:

|Module / Entity Name|Alias|
|---|---|
|random|rd|
|randint|ri|
|choice|ch|

2. Modify the rest of your code to make it work with your modified import command.
2. Run your program to test, troubleshoot as needed, and save.
5. Commit and push your file to GitHub (including the message, 'Updated lab (import w/aliases).')

**PART F:**
1. Copy/paste the code below to the bottom of your file.
2. Respond to each reflection question/prompt within a comment.
3. Commit and push your file to GitHub (including the message, 'Updated lab (reflection).')

```python
# Reflection Questions:

# 1. In your own words, describe what modules are and how they can be used to organize programs:

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 2. In your own words, describe what a program's namespace is:

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 3. Why might a programmer choose to import only a few entities from a module rather than importing the entire module or all entities from the module?

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 4. Why will the following lines of code result in an error, and what can be done to fix the error?

#
# import math
# print(pi)
#

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 5. Why will the following lines of code result in an error, and what can be done to fix the error?

#
# from math import pi
# print(math.pi)
#

# REPLACE THIS TEXT WITH YOUR RESPONSE.

# 6. Why will the following lines of code result in an error, and what can be done to fix the error?

#
# import math as ma
# print(math.pi)
#

# REPLACE THIS TEXT WITH YOUR RESPONSE.
```

**HOMEWORK:** 

Reading: https://edube.org > Sign In > Python Essentials 2 > 1.1.1.1 - 1.2.1.8


**Note:** If you have not successfully completed all configuration tasks and the random lab by the end of class, you must see Mr. Swotinsky at the end of the day for support.

##
**REFERENCE:**

|To...|Code...|
|-|-|
|...import a module as a whole.|`import module_name`|
|...import an entity from a module.|`from module_name import entity_name`|
|...import multiple entities from a module|`from module_name import entity_1_name, entity_2_name,...`|
|...import all entities from a module|`from module_name import *`|
|...import a module with an alias|`import module_name as alias_name`|
|...import entities with aliases|`from module_name import entity_1_name as alias_1, entity_2_name as alias_2,...`|
|...call on an entity in a program<br><br>(If the module was imported as a whole.)|`module_name.entity_name`|
|...call on an entity in a program<br><br>(If the entity was imported or if all entities were imported.)|`entity_name`|



## Configuration Task 1: Download Git to your virtual machine:

1. Open a web browser and navigate to https://git-scm.com/downloads
2. Click the top link to download the latest version of Git for Windows.
3. Run the installer.
4. On the <ins>Select components</ins> screen, select <ins>Additional Items</ins>, and <ins>On the Desktop</ins>.  Do not make any other changes.

## Configuration Task 2: Clone your Computer_Science_Portfolio Repo.

*During this process, you may be prompted to sign in to GitHub again.*
1. Launch Git Bash using the icon on the desktop of your virtual machine. 
2. Change the directory to your Python312 folder by entering the command below:
```
cd AppData/Local/Programs/Python/Python312
```
3. Clone your repo by entering the command below: 

**Note: In the command below you must change `YourGitHubUserName` to your actual GitHub username.**

```
git clone https://github.com/YourGitHubUserName/Computer_Science_Portfolio.git
```
4. Change the directory to your newly cloned Computer Science Portfolio repo by entering the command below:

```
cd Computer_Science_Portfolio
```
5. Create a sub-directory for Data Science 1 by entering the command below:
```
mkdir Python_2
```

## Configuration Task 3: Write a small batch file to launch the Python IDLE from your Python 2 repo directory.

**PART A:** Write your batch file:
1. Open Notepad.
2. Copy/Paste the code below to your file:
```
cd..

cd AppData\Local\Programs\Python\Python312\Computer_Science_Portfolio\Python_2

idle
```

**PART B:** Save your batch file:
1. For <ins>Save as type</ins>, select <ins>All Files</ins>.
2. For <ins>Encoding</ins>, select <ins>ANSI</ins>.
3. Name your file `IDLE_launcher.bat`.
4. Save `IDLE_launcher.bat` to your virtual machine's desktop.


## Configuration Task 4: Test your configuration.

**PART A:** Create a test file:

1. Use the IDLE launcher you created in configuration task 3 to launch the Python IDLE.
2. Click <ins>File</ins>.
3. Select <ins>New File</ins>.
4. Save your file as, **LastNameFirstInitial_Lab01_Random.py**.
5. Copy/Paste the code below to the first cell of your notebook:

```python
# Random Number Generator Lab
```

6. <ins>Save</ins> your file.

**PART B:** Push your notebook to your repo:

1. Launch Git Bash. 
2. Navigate to the Python 2 subdirectory of your Computer Science Portfolio repo by entering the command below:

```
cd AppData/Local/Programs/Python/Python312/Computer_Science_Portfolio/Python_2
```

3. Track your `LastNameFirstInitial_Lab01_Random.py` file by entering the command below:

```
git add LastNameFirstInitial_Lab01_Random.py
```

4. Commit your changes to `LastNameFirstInitial_Lab01_Random_Number_Generator.py` file (including the message: 'Uploaded v0 of random number generator lab.')by entering the command below :

```
git commit LastNameFirstInitial_Lab01_Random.py -m 'Uploaded v0 of random number generator lab.'
```

5. Push your repo to GitHub by entering the command below :

```
git push
```
6. Navigate to your Computer Science Portfolio on GitHub to confirm that the `Python_2` subdirectory and `LastNameFirstInitial_Lab01_Random.py` are visible.

### Congratulations! Your device is now configured for Python 2!

## If you run into any challenges, remember to troubleshoot by...
* ...reviewing the directions above.
* ...consulting with colleagues.
* ...asking for help.
* ...consulting web-based resources.
* ...etc.
