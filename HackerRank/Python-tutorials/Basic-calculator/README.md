#[Basic calculator](https://www.hackerrank.com/challenges/basic-calculator)
######Problem Statement
Lets build a calculator! You are given two real numbers and your task is to print the

    Addition
    Subtraction
    Multiplication
    Divison
    Integer Divison

of the two numbers in 5 separate lines. Keep a precision of two digits after decimal.
######Input Format 
The first line contains one float number

The second line contains another float number
######Output Format
Print the output for each operation in different lines.
######Sample Input
```
2.3
4
```
######Sample Output
```
6.30
-1.70
9.20
0.57
0.00
```
######Constraints
-10000 <= First number <= 10000
-10000 <= Second number <= 10000 
######Concept
Numbers are of 2 types :
1. Integers (eg: 1, -5, 4, 0)

2. Real Numbers (eg: 2.2, -4.4, 3.99) i.e. any number with decimal values

When we divide 2.3 by 4, we get 0.575 , which is a real number. But sometimes, we just want to get an integer value. In that case // operator is used which divides the two numbers, and returns an integer value. This is called integer divison.

NOTE : // operation is generally used in divison of two integers.

When the user enters a value, python reads it as a string. So, we need to change it from string to real number. In python, real numbers are called float data type. So when the user inputs a number, it needs to be converted to float data type. Eg:
```
>> l = float(input('Enter the length : '))
```
If we need to convert a real number to string, use **str()** function. Eg :
```
>> a = 5.2
>> a= str(a)
```
If we need to see what type of data type a variable is, use **type()** function.
```
>> type(num)
<class 'int'>
```
Note : All data types are not interconvertible. If in a string, there are some alphabets and you convert it to an integer, an error will be returned.
