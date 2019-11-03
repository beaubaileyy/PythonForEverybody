# PythonForEverybody

Goals (high level intended outcomes; for software, a Product Backlog)

Boundaries / Scope (where the functions and responsibilities of the solution start and end / what it should do and what is left to other systems to do)

Success criteria (set of conditions to be satisfied at completion; must be measurable and verifiable, like a test)

Constraints (externally imposed limitations on system requirements, design, or implementation or on the process used to develop or modify a system)

Assumptions (things that are accepted as true or as certain to happen, without proof)

Stakeholders (individuals or organizations having a right, share, claim, or interest in a system or in its possession of characteristics that meet their needs and expectations)

Timelines (for software, a breakdown of high level goals like from the Product Backlog into time-bound smaller, more detailed tasks, like in Sprint Backlogs)

Goals
---------
Complete the Python for Everybody Specialization

Boundaries / Scope
-------------------
Complete Course 1 Programming for Everybody (Getting Started with Python) 
Complete Course 2 Python Data Structures

Success criteria
-----------
My own application for data retrieval and processing.
Weekly work log with screenshots and summaries to demonstrate activity.

Constraints
-
I will be auditing the course for free so will be able to read and view the course content but not submit projects or earn the certification.

Assumptions
----
The courses will be available for the duration of the semester.
I have all required software.
I can skip the Installing and Using Python units.

Stakeholders
-
Professor - for grade

Parents - investing in my education and future success, want to make them proud

Perspective Employers - artifact will be added to my student portfolio which could help with getting a job


Timeline
-
Week: 

Chapter One - Why we Program? (3 hours)

Chapter Two: Variables and Expressions (3 hours)

Chapter Three: Conditional Code (3 hours)

Chapter Five: Loops and Iteration (3 hours)

Chapter Four: Functions (2 hours)

Chapter Seven: Files (3 hours)

Chapter Eight: Lists (3 hours)

Chapter Six: Strings (3 hours)

Chapter Nine: Dictionaries (3 hours)

Chapter Ten: Tuples (2 hours)

Graduation and work on independent program (2 hours)

Complete independent program (2 hours)

-

Chapter 1: (2 hours)
-

Started to go through the basic introductions of the course. Learned about the instuctor and some of the very basics of the course and why it was made. Ended after the "Why program?" section. Mostly this section was about why programming is important and why people should have some basic knowledge of the course.

Then he just went over installing python and getting it ready for use on your own computer. He went over on how to download it on the main platforms such as windows and mac.

He then briefly covers sequential steps and how computers simply go from one thing to the next thing. He then talks about conditional statements and how they lead to different answers.

**Sequential steps** - the computer goes line by line and runs every single line of code 

**Conditional statements** - if the certain criteria is true or false the computer will follow different paths of code depending upon user input (if statements)

**Repeated steps** - These statements run code multiple times until certain criteria is met, for example with loops they have iteration variables that change each time the code is ran and basically force the code to run only a certain amount of times (for and while loops)

Chapter 2 : (2 hours)
- 

**Constants** - value does not change, numeric values and strings are constants 

**Reserved words** - words that have some special function in python that you cannot use as variable names or identifiers

**Variables** - a name you choose to identify something with, is stored in the memory so a programmer can store data and then retrieve it later through the variable name. You can even change the contents assigned to the variable in a later statement.
  - must start with a letter or underscore 
  - must only consist of letters, numbers, and underscores 
  - are case sensitive 
A good variable name is something that is friendly to the user and easily identified 

**Assignment statements** - we assign a value to a variable using the assignment statement (=) an assignment statement consists of an expression on the right hand side and a variable to store the result

**Operator precedence** - When you string together operators in python it need to know what to do first, you indicate this through use of parenthesis

**Operator precedence rules** - highest to lowest: Parenthesis, power, multiplication (and division and remainder), addition (and subtraction), and left to right

Python knows the difference between integers and strings, however python cannot add an interger to a string.
You can use the type() function to distinguish whether something is an integer or string

**Types of numbers:**

Integers - whole numbers 
Floating point numbers - have decimal points
There are other number types that are variations of floats and integers 

**Type conversions** - when you put an integer and floating point number in an expression, the integer is implicitly converted to a float. You can control this with the functions float() and int()

**Integer division** - integer division produces a floating point result

**String conversions** - You can use float() and int() to convert between strings and integers, you will get an error if the string does not contain numeric characters 

**User input** - You can instruct python to pause and read data from the user using input() function, this function returns a string 

**Comments in python** - anything after a # is ignored in python
  - comments can help you describe what code is doing
  - document who wrote the code
  - turn off a line of code (maybe temporarily)

Chapter 3: (3 hours)
- 

**If statement:**
  - reserved word that indicates you're going to be doing something conditionally
  - if the criteria is true then it executes the code, if it is false it moves onto the next condition and tests the same thing over again 
  - certain code may or may not run 
  - one way decision 

**Comparison operators:** 
 - Boolean expressions asks a question and produces a yes or no result which you can use to control program flow
 - Boolean expressions using comparison operators evaluate to true/ false or yes/ no
 - Comparison operators look at variables but do not change the variables
 
 **INDENTATION IN PYTHON IS VERY IMPORTANT**
 There can be a difference between tab and the proper amount of spaces for an indent, most text editors turn tabs into spaces
 Incorrect indentation can lead to errors in python 
 Using spaces (4) is reccomended over using tab
 
 **Two-way decisions:**
 - Sometimes you want to do one thing if a logical expression is true and something else if the expression is false 
 - Like a fork in the road, must choose one path or the other, not both 
 
**Else statment:**
 - within an if statement 
 - introduces another condition within the if statement
 
 **Elif statement:**
 - Combination of else and if 
 - Can test multiple conditions
 - Once one of the conditions is met it skips the rest of the code and prints result
 - Runs until one of the conditions is met
 - Starts with if then followed by however many elif statements 
 - Can contain else at the end or you can leave else out 
 - If there is an else statement at the end then at least one condition will be met, if there is no else its possible to not meet any conditions 
 - Can have LOTS of elifs 
 
 **Try/ except structure:**
 - You surround a dangerous part of code with try and except
 - If the code in the try works, the except is skipped 
 - If the code in the try fails, it jumps to the except section 
 - Usually used to test for errors within code without python actually stopping your code 
 
Chapter 4: (2 hours)
-
 
 Using the def function you can essentially store lines of code within your own function for use later
 
 **max() function** - can search for things within an input, for example it can search for biggest letter or the smallest.
 
 **Type conversions:**
 - When you put an integer and floating point in an expression, the integer is implicitly converted to a float
 - You can control this with the built in functions **int()** and **float()**
 
 **String Conversions:**
 - You can also use **int()** and **float()** to convert between strings and integers 
 - You will get an error if the string doesn't contain numeric characters
 
 **Building your own functions:**
 - You create new functions using the **def** keyword
 - Indent the body of the function
 - This defines the function but does not execute the body of the function
 - You need to reuse (call or invoke)the code you defined in order for python to execute it 
 
**Arguments:**
- An argument is a value you pass into the function and its input when we call the function 
- You use arguments so you can direct the function to do different kinds of work when you call it at different times
- You put the arguments in the parenthesis after the name of the function 

**Parameter:** 
- A paramter is a variable which you use in the function definition. It is a "handle" that allows the code in the function to access the arguments for a particular function invocation
- Allows for you to have code that is almost the same but does something a little different than another parameter 

**Return Values:**
- Often a function will take its arguments, do some computation, and return a value to be used as the value of the function call in the calling expression. The return keyword is used for this.
- A "fruitful" funtion is one that produces a return value (or result)
- A "nonfruitful" function is one that does not produce a return value
- The return statement ends the function execution and "sends back" the result of the function

**Multiple parameters/arguments:**
- You can define more than one parameter in the function definition 
- You simply add more arguments when you call the function 
- You match the number and order of arguments and parameters

Chapter 5: (2 hours)
- 

**Repeated steps:**
- Loops (repeated steps) have iteration variables that change each time through a loop. Often these iteration variables go through a sequence of numbers

**Infinite loop:**
- Doesn't have an iteration variable, will run forever 

**Breaking out of a loop:**
- The **break** statement ends the current loop and jumps to the statement immediately following the loop
- It is like a loop test that can happen anywhere in the body of the loop

**Continue statement:**
- The **continue** statement ends the current iteration and jumps to the top of the loop and starts the next iteration 

**Definite loop:**
- Is finite
- Go over all the lines of code 
- For definite loops you use the **for** construct
- Definite (for loops) have explicit iteration variables that change each time through a loop. These iteration variables move through the sequence or set

**In statement:**
- The iteration variable "iterates" through the sequence (ordered set)
- The block (body) of code is executed once for each value in the sequence
- The iteration variable moves through all of the values in the sequence

**Making "Smart Loops"** 
- The trick is "knowing" something about whole loop when you are stuck writing code that only sees one entry at a time 
- Set some variables to initial values 
- for thing in data: Look for something or do something to each entry seperately, updating a variable 
- Look at the variables 

**Counting in a loop:**
- To count how many times we execute a loop, we introduce a counter variable that starts at 0 and we add one to it each time through the loop

**Summing in a loop:**
- To add up a value we encounter in a loop, we introduce a sum variable that starts at 0 and we add the value to the sum each time through the loop

**Finding the average in the loop:**
- An average just combines the counting and and sum patterns and divides when the loop is done

**Filtering in a loop:**
- We use an if statement to catch/ filter in the values we are looking for 

**Search using a Boolean Variable:**
- If you just want to search and know if a value was found, you use a variable that starts at false and is set to true as soon as we find what we are looking for

Chapter 6: (2 hours)
- 

**6.1 - Strings**

**String Data Type**
- A string is a sequence of characters 
- A literal string uses quotes 'hello' or "hello"
- for strings, + means "concatenate"
- when a string contains numbers, it is still a string
- we can convert numbers in a string into a number using int()

**Reading and Converting Strings**
- We prefer to read data in using strings and then parse and convert the data as we need it 
- This gives us more control over error situations and/or bad user input 
- Input numbers must be converted from strings

**Looking Inside Strings**
- We can get at any single character in a string using an index specified in square brackets 
- The index value must be an integer and starts at zero
- The index value can be an expression that is completed

**A Character Too Far**
- You will get a python error if you attempt to index beyond the end of a string
- So be careful when contructing index values and slices

**Strings Have Length**
- The built in function len gives us the length of a string

**Looping Through Strings**
- Using a while statement and an iteration variable, and the len function, we can construct a loop to look at each of the letters in a string individually
- A definite loop using a for statement is much more neat 
- The iteration variable is completely taken care of by the for loop

**Looping and Counting**
- See attachment "Looping and counting"

**Looking Deeper into in**
- The iteration variable "iterates" through the sequence (ordered set)
- The block (body) of code is executed once for each value in the sequence
- The iteration variable moves through all of the values in the sequence 

**Slicing Strings**
- We can also look at any continuous section of a string using a colon operator
- The second number is one beyond the end of the slice - "up to but not including"
- If the second number is beyond the end of the string, it stops at the end
- See attachment "Slicing Strings" for example

**6.2 - Manipulating Strings**

**String Concatenation**
- When the + operator is applied to strings, it means "concatenation"

**Using in as a Logical Operator**
- The in keyword can also be used to check to see if one string is "in" another string
- The in expressoin is a logical expression that returns TRUE or FALSE and can be used in an if statment

**String Library**
- Python has a number of string functions which are in the string library
- These functions are already built into every string - we invoke them by appending the function to the string variable
- These functions do not modify the original string, instead they returrn a new string that has been altered

**Searching a String**
- We use the find() function to search for a substring within another string
- find() finds the first occurance of the substring
- If the substring is not found, find() returns -1
- Remember that string position starts at zero 

**Making Everything UPPER CASE**
- You can make a copy of a string in lower case or upper case 
  - .upper()
  - .lower()
- Often when we are searching for a string using find() we first convert the string to lower case so we can search a string regardless of case

**Search and Replace**
- The replace() function is like a "search and replace" operation in a word processor
- It replaces all occurences of the search string with the replacement string

**Stripping Whitespace**
- Sometimes we want to take a string and remove whitespace at the beginning and/or end
- lstrip() and rstrip() remove whitespace at the left or right
- strip() removes both beginning and ending whitespace

Chapter 7: ( hours)
- 

**7.1 - Files**



Chapter 8: ( hours)
- 



Chapter 9: ( hours)
- 



Chapter 10: ( hours)
- 


