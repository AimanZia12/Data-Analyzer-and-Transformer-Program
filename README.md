# Data Analyzer and Transformer Program

## This python program is built for Data Analyzer and Transformer Program is an application which is a menu-driven and which allows users to perform several data analysis and transformation operations.

## Features

### 1. Data Acquisition

* Give options to user to insert data manually or take sample data.
* Data is being stored in a Python list.

### 2. Data Summary Representation

Built-in functions of Python provides the following informations:

* Total number of elements
* Sum of all values
* Maximum value
* Minimum value
* Average value
* Duplicate values in the dataset.
* Captures unique values in the dataset.

### 3.Factorial (Recursion) Calculation

* It is used to calculate factorial of a number.

### 4. Filtering Data (Lambda Function)

* It is used to filters values greater than a specific threshold entered by the user.
* For this, following is used:

  * filter()
  * lambda
  * map()

### 5. Display Dataset Statistics

In this displaying of dataset statistics is done when user input multiple values -

* For accepting multiple values *args is used.
* For displaying summary of statistics for dataset **kwargs is used.

**kwargs displayed the following statistics:

* Total values
* Sum of values
* Maximum value
* Minimum value
* Average value

### 6. Sort Data

In this Data is sorted and two options have been given to the user which are:

* Ascending Order Sorting
* Descending Order Sorting

It uses following functions for sorting the data and for generating new sorted data.

* sort()
* sorted()

### 7. Exit Program

Choosing uoption 7 user exit the program.

## Technologies Used

* Python 3
* Functions
* Recursion
* Lambda Functions
* Built-in Functions
* List Operations
* *args
* **kwargs

## Working Flow
 
1. Main Menu options are appeared to user from which user can select an option according to his requirement, and on the basis of these options one by one tasks are being done.

Main Menu

1. Input Data- Here two options have been provided to the user to manually write their 1D list or take sample 1D Lists for further tasks.

2. Display Data Summary - Built functions using UDF and applied simple built in functions like len(), sum(), max(), min(), also found duplicate and unique values present in the dataset.

3. Calculate Factorial - Built a recursion function for calculating factorial of a number given by the user.

4. Filter Data by Threshold - User provided a threshold value on the basis of which data is being filtered, and mapped using filter() and map() functions.
 
5. Display Dataset Statistics - Using *args we taken multiple values and then displayed datset statistics using **kwargs and also used global variable for summarizing.

6. Sort Data - Data is being sorted into ascending order and descending order using sort() function also new sorted list is being created using sorted() function.

7. Exit Program - User exit the program.

