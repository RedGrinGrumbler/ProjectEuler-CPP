# Sum of Even Fibonacci Numbers #

https://projecteuler.net/problem=2

## Problem Description ##


Each new term in the Fibonacci sequence is generated by adding the previous two terms. By starting with 1 and 2, the first 10 terms will be:

1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...

By considering the terms in the Fibonacci sequence whose values do not exceed four million, find the sum of the even-valued terms.


## Over View ##

The Main thing here is just setting the correct parameters 
It says starting from 1 and 2, but this outputs 2 different values from 1 & 1 to 1 & 2. 
I made 2 Functions aside from main, there is display() and sumUp(). 

Display helps manage the messiness of the code by removing any printf() statements. 

sumUp() is the meat and potatoes, it reads a ceiling and 2 starting INTs, then it can 
pass its Sum Value and current Fibonacci sequence value. 
