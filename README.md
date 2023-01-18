# Lab Instructions: Functions, loops and data structures

In this lab you will be presented with a menu ordering system which will allow users to   
input three choices for a select menu. You are tasked with completing the menu system so   
that it returns and calculates the final bill for the user.
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
