# Lab Instructions: Functions, loops and data structures

In this lab you will be presented with a menu ordering system which will allow users to   
input three choices for a select menu. You are tasked with completing the menu system so   
that it returns and calculates the final bill for the user.
 <br><br>

> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file sin Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
> - Questions about using VSCode? Please see our support resources [here](https://www.coursera.org/learn/programming-in-python/supplement/2IEyt/visual-studio-code-on-coursera).
> #### **To run your Python code**
> - Select your Python file in the Visual Studio Code file tree 
> - You can right click the file and select "Run Python File in Terminal" 
>   or run the file using the smaller   
    play button in the upper right-hand corner 
>   of VSCode.  
    (Select "Run Python File in Terminal" in the provided button dropdown)
> - Alternatively, you can follow lab instructions which use python3 commands to run your code in terminal.
> 

<br> 

## There are three main objectives of this activity:
1. Create new functions to solve specific problems.
2. Gain experience of using for loops to iterate over different data collections.
3. Create and use data structures to store, retrieve and loop over data.

<br>

## Exercise Instructions

1. Open the script ordering_system.py present inside the project folder.

2. Run the script and, when requested, enter in the three products of your choice based on the menu - 1 = espresso, 2 = coffee etc.

3. To run the script, open terminal and execute the following command. 

    ```
    python3 ordering_system.py
    ```

4. Extend the script to have a new function called `calculate_subtotal`.  
 It should accept one argument which is the order list and return the sum   
 of the prices of the items in the order list.

5. Implement `calculate_tax()` which calculates the tax of the subtotal.   
The tax percentage is 15% of overall bill.

6. Implement `summarize_order()` which returns a list of the names of the items   
that the customer ordered and the total amount (including tax) that they have to pay.  
 The orders should show the name and price.

<br>

## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
# Lab: Read in data, store, manipulate and output new data to a file

In this lab you'll read the contents of a file and then write the contents to another file.  
You'll store the contents of a file into a list so that it can be accessed in different ways. 
 <br><br>

> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
> - Questions about using VSCode? Please see our support resources [here](https://www.coursera.org/learn/programming-in-python/supplement/2IEyt/visual-studio-code-on-coursera).
> #### **To run your Python code**
> - Select your Python file in the Visual Studio Code file tree 
> - You can right click the file and select "Run Python File in Terminal" 
>   or run the file using the smaller   
    play button in the upper right-hand corner 
>   of VSCode.  
    (Select "Run Python File in Terminal" in the provided button dropdown)
> - Alternatively, you can follow lab instructions which use python3 commands to run your code in terminal.
> 

<br>

## There are two objectives of this activity: 
1. Create a function for reading in a file

2. Create a function for writing files.
 <br><br>


## Exercise Instructions:  
<br>

1. Check that the `sampletext.txt` and `file_ops.py` files exist and are present inside the project folder.   
   You can run the `file_ops.py` file by opening a terminal and executing the following command:
    ```
    python3 file_ops.py 
    ```

2. Complete the `read_file()` function to read in the sampletext.txt file using the `open` function and return the entire contents of the file. 

3. Complete the `read_file_into_line()` function so that it returns a data structure of all the contents of the file in a line-by-line sequential order.

4. Fill in the `write_first_line_to_file()` that accepts two arguments. This should write only the first line of the file contents into the given output file.   

    - **Argument 1:** The contents of a file to be written
    - **Argument 2:** The name of an output file.
<br><br>


5. Complete the `read_even_numbered_lines()` to return a list of the even-numbered lines of a file (2, 4, 6, etc.) 

6. Fill in the `read_file_in_reverse()` function to return a list of the lines of a file in reverse order. 

<br>

## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
<br> <br> 

# Lab Instructions: Mapping key-values to Dictionary data structures 

So far you have learned that Python has different techniques to modify a given iterator sequence such as list or dictionary using comprehensions,  
map() function and so on. Now you will be utilising what you have learned. Let’s say you have a list of employee data for the Little Lemon company.  
You want to create login accounts for the employees and you will create usernames for these employees in the first example. 

You also want to update the roster for these employees on the calendar and want easy access to their initials and employee IDs, as they are all unique.  
To get that, in the second example, you will create a dictionary with the required information. 
<br><br>

> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
> - Questions about using VSCode? Please see our support resources [here](https://www.coursera.org/learn/programming-in-python/supplement/2IEyt/visual-studio-code-on-coursera).
> #### **To run your Python code**
> - Select your Python file in the Visual Studio Code file tree 
> - You can right click the file and select "Run Python File in Terminal" 
>   or run the file using the smaller   
    play button in the upper right-hand corner 
>   of VSCode.  
    (Select "Run Python File in Terminal" in the provided button dropdown)
> - Alternatively, you can follow lab instructions which use python3 commands to run your code in terminal.
> 
 <br><br> 

## Exercise Instructions

1. Open the `comprehensions.py` file

2. Implement the `to_mod_list()` function by using the `map()` function to apply `mod()`
   to all elements within `employee_list`.  
    Assign the result of it to a new variable called `map_emp`. Convert `map_emp` to a list and return it. 
   - The `mod()` function returns a string value for example such as `“Lisa_Cold Storage”` from the dictionary passed to it. <br><br>

3. At this point you should have a list of the values such as: `“Lisa_Cold Storage”` mentioned above.  
But that is no good for a username with the whitespace present in it.  
    - Implement the `generate_usernames()` method by using list comprehension and the `replace()` over `mod_list`  
  to replace all spaces `(" ")` with underscores `("_")`. 
    - Return the resulting list. <br><br>

4. We want to create a dictionary that stores employees' first initials and IDs. 
    - Implement `map_id_to_initial()` by using dictionary 
comprehension over the `employee_list` to create a dictionary   
where each key is the 
first letter of an employee's name and the value is the employee's ID.<br><br>

5. Run the script by opening the terminal and executing the command:
    ```
    python3 comprehensions.py
    ```

<br>


## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
<br> <br> 

# Lab Instructions: Abstract Classes and Methods

In this assignment, you will be creating an abstract class for a bank that will be used to create a regular class for a specific bank.  
This class will contain the implementation of the abstract method from the abstract class.  

 <br>

> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
> - Questions about using VSCode? Please see our support resources [here](https://www.coursera.org/learn/programming-in-python/supplement/2IEyt/visual-studio-code-on-coursera)
> #### **To run your Python code**
> - Select your Python file in the Visual Studio Code file tree 
> - You can right click the file and select "Run Python File in Terminal" 
>   or run the file using the smaller   
    play button in the upper right-hand corner 
>   of VSCode.  
    (Select "Run Python File in Terminal" in the provided button dropdown)
> - Alternatively, you can follow lab instructions which use python3 commands to run your code in terminal.
> 
<br>

## Exercise Instructions

### Instructions

1. Create a class called `Bank` and pass `ABC` to it.  

2. Inside the class you have to define two methods: 
    - 2.1: Define a function called `basicinfo()` and add a print statement inside it saying   
    `"This is a generic bank"` and returning the string `"Generic bank: 0"`. 

    - 2.2: Define a second function called `withdraw` and keep it empty by adding a pass keyword under it.   
    Make this function abstract by adding `'@abstractmethod'` right above it. <br><br>

3. Create another class called `Swiss` and pass the class `Bank` inside it. 
    This means you are inheriting from `class Bank`. 
    -  3.1: Create a constructor for this class that initializes a class variable `bal` to `1000` <br><br>

4. Override both functions from the Bank class: `basicinfo()` and `withdraw()`. 
    - 4.1: Define a function called `basicinfo()` and add a print statement inside it stating `“This is the Swiss Bank”`  
    and returning a string with `"Swiss Bank: "` followed by the current bank balance.   
    For example, if `self.bal = 80`, then it would return `"Swiss Bank: 80"`

    - 4.2 Define a second function,  called `withdraw` and pass one parameter to it (other than `self):` amount.  
     Amount represents the amount that will be withdrawn. 

        - 4.2.1: Update the class variable bal by deducting the value of amount from it. 
        - 4.2.2: Print the value of amount giving output such as: “Withdrawn amount: 30"
        - 4.2.3:  Print the new balance giving an output such as: “New balance: 970”
        - 4.2.4:  Return the new balance
        - Note: Make sure to verify that there is enough money to withdraw!  
        If amount is greater than balance, then do not deduct any money from the 
        class variable `bal`. Instead, print a statement saying `"Insufficient funds"`, and return the original account balance instead.

<br>


## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
<br> <br> 

# Lab Instructions: Import and Scope

So far, you've learned the different ways in which you can use import statements to import other Python files, modules and packages.   
You have also seen the different ways in which you can import specific functions using different formats of import.   
In this assignment you'll learn and practice how to use import to bring external code within the direct scope of the project.

 <br>

> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
> - Questions about using VSCode? Please see our support resources [here](https://www.coursera.org/learn/programming-in-python/supplement/2IEyt/visual-studio-code-on-coursera).
> #### **To run your Python code**
> - Select your Python file in the Visual Studio Code file tree 
> - You can right click the file and select "Run Python File in Terminal" 
>   or run the file using the smaller   
    play button in the upper right-hand corner 
>   of VSCode.  
    (Select "Run Python File in Terminal" in the provided button dropdown)
> - Alternatively, you can follow lab instructions which use python3 commands to run your code in terminal.
> 

<br>

## Exercise Objectives:
- Use the import statement to import a built-in package in Python.
- Use the import statement to call a function present in another Python file. 
<br><br>

## Instructions

1.  Open the file jsongenerator.py present inside project folder.

2. Import a built-in package called `json` 
   
3. Import the following from a file called employee.py:
   - A function called `details` 
   - Variables called `employee_name`, `age` and `title`
<br><br>

4. Implement the `create_dict()` function that returns a dictionary given employee information.   
Create and return a dictionary with three key-value pairs where:
    - Keys are string variables: `"first_name"` `“age”` and `“title”`  
     and their respective values are `employee_name`, `age` and `title` variables that we have imported from the employee module. 
    - Be sure to cast the values to the expected types.
<br><br>

5. Use a function called `dumps()` from the json module using dot notation and pass the `employee_dict` dictionary that we have created to it.   
Return its value to a variable named `json_object`. 

    The format of the same should look like:
    ```
    variable = json.dumps(dict) 
    ```

6. Complete the `write_json_to_file()` function
    - Use a built-in function called `open()` and pass the `output_file` argument and `“w”` to it.   
    Return the value of this function to a variable named newfile.
    -   Call a function called `write()` over this variable newfile. Pass the `json_object` variable you created in Step 5 inside it.
    - Close this file by calling a built-in function `close()` directly on newfile. You don’t need to pass any arguments here. 
<br><br>


7. Save the files

8. Open the terminal to execute the files

9. Run the code using the command (within project directory)
   ```
    python3 jsongenerator.py 
    ```

<br>


## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
<br> <br> 

# Lab Instructions: Write a test

In this exercise, you'll learn how to create test cases for a given block of code using PyTest.  

You will be checking the accuracy of a string input to a given function against some conditions and writing two functions:
- **The first function** will check if the length of the input string is within a   
specific limit of words and characters. 
- **The second function** will check if the basic grammar of the string is well-defined.
 <br><br>

> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
> - Questions about using VSCode? Please see our support resources [here](https://www.coursera.org/learn/programming-in-python/supplement/2IEyt/visual-studio-code-on-coursera).
> #### **To run your Python code**
> - Select your Python file in the Visual Studio Code file tree 
> - You can right click the file and select "Run Python File in Terminal" 
>   or run the file using the smaller   
    play button in the upper right-hand corner 
>   of VSCode.  
    (Select "Run Python File in Terminal" in the provided button dropdown)
> - Alternatively, you can follow lab instructions which use python3 commands to run your code in terminal.
> 

<br>

## Objective of this activity:   
Ensure the string variables that will be passed as arguments to the code are within a specified length and have a well-defined structure.<br><br>

## Instructions:

1. Open the `test_spellcheck.py` file inside the project folder.

2. Import the `pytest` and `spellcheck` modules.
3. Comment out the beta variable using # symbol for now. 
4. Next, complete the `test_length()` and `test_struc()` functions.   
   These two functions use input_value to check if the functions defined in spellcheck behave correctly. 
5.  In `test_length()` function, you must add two assert statements.   
    In each assert statement you first need to call the required function from the spellcheck file that you imported,  
    and then check against some conditions. For example, the format will be similar to the following against some condition:
    ```
    assert spellcheck.some_function(input_value)
    ```
    - 5.1: Add the first assert statement over `function word_count()` from the main code which asserts that the returned value is less than 10.
    - 5.2: Add the second assert statement over `function char_count()` from the main code which asserts that the returned value is less than 50. 
<br><br>

6. In the second function `test_struc()`, you must add two assert statements. The first assert statement checks if the first character is in upper case.  
The second assert statement checks if the sentence or the string variable passed ends with a dot (“.”) 
    - Add the first assert statement over function `first_char()` from the main code.  
      Now call a built-in function `isupper()` directly over it, such as `function_name.isupper()`. 
    - `isupper()` function returns True if it is called over an upper-case character and False if called over a lower-case character.  
      For example, `"A".isupper()` returns `True` and `"a".isupper()` returns `False`.
    - Add the second assert statement over the function `last_char()`from the main code and compare it to `“.” ` 
<br><br>

7. Save the files.
8. Open the terminal to execute the files.
9. Run the code using the following command (within the  project directory):
    ```
    python3 -m pytest test_spellcheck.py 
    ```
10. Both the tests should pass in this case.  


- **BONUS STEP:**<br>
Pass the variable beta instead of alpha in all four of the functions.  
The result should now show one passed and one failed test.  

<br>

> **Tips**<br>
> Be sure to double check some common mistakes made in this process 
  below before submitting!  
> - Forgetting to import the `pytest` and `main` code file
> - Not passing the variable names correctly
> 
<br>


## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
<br> <br> 