# Functions
​

## 0. Reversing a String
Write a Python program to reverse a string.

Sample String : "1234abcd"
Expected Output : "dcba4321"

**Remember how to get the last index?** 

## 1. Finding Sum,Subtraction and Multiplication

Define a function that accepts 2 values and return its sum, subtraction and multiplication.

**Example :**

Input:

a = 5 , b = 2

Output:

Sum is = 7 , Sub is = 3, Multiplication is  =10

## 2. Calculating the Factorial

Write a Python function to calculate the factorial of a number (a non-negative integer). The function accepts the number as an argument.

## 3. Finding Max

Write a Python function to find the Max of three numbers.


## 4. Check Prime

 Write a Python function that takes a number as a parameter and check the number is prime or not.

## 5. Future of TL
Write a function which takes 3 inputs as **current_balance**, **yearly_inflation_percentage** and **years**, and returns the future value of TL after **years** pass, rounded to 2 decimals (assuming constant inflation rate).

**Example:**  
```
future_of_TL(10000, 20, 1) -> 8000.00
future_of_TL(350000, 16.72 , 5) -> 202157.66
```
​
## 6. Making Chocolate 
​
We want to make a package of `target` kilos of chocolate. We have small bars (**1 kilo each**) and big bars (**5 kilos each**) and our goal is to sum a varying number of them to obtain `target` kilos.
​
Write a function `make_chocolate(small_bars, big_bars, target)` where
​
* `small_bars` is the number of small bars available,
* `big_bars` is the number of big bars available,
* `target` is the number of kilos of chocolate to make.
​
Return the number of small bars to use, assuming we always use big bars before small bars. Return `-1` if it cannot be done.
​
```
make_chocolate(4, 1, 9) → 4
make_chocolate(4, 1, 10) → -1
make_chocolate(4, 1, 7) → 2
```
​
## 7. Convert to Binary
Write a function which takes an integer input (base 10), converts it into binary (base 2) and returns the result.   

**Examples:**
```
convert_to_binary(10) -> 1010
convert_to_binary(32) -> 100000
```
​
​
## 8. Find Greatest Common Divisor (GCD)
Write a function which takes 2 positive integers and returns their greatest common divisor as an integer.  

**Example:** 
```
find_gcd(24,32) -> 8
find_gcd(5,4) -> 1
``` 
**To-do:** Try coding Least Common Multiple (LCM) as well.
​

​
## 9. Time Difference
Write a function which takes 2 string inputs in the format HH:MM:SS (on 24h basis) and returns 3 integers: the absolute time difference in seconds, in minutes (rounded down), in hours (rounded down).  

**Example:**
```
time_diff("15:23:46", "20:08:35") -> 17089, 284, 4
time_diff("06:12:59", "09:50:03") -> 13024, 217, 3
```   
​
​
## 10. Check Prime
Write a function which takes a non-negative integer input, checks if it is a prime number, and returns True/False accordingly.   

**Examples:** 
```
check_prime(17) -> True
check_prime(27) -> False
```
​
​
## 11. List Prime Numbers
Write a function which takes 2 integer inputs as search limits (both including) and returns a list of prime numbers in between. Use your **check_prime()** function from previous exercise to check if a number is prime.   

**Examples:** 
```
list_primes(23 10) -> [11, 13, 17, 19, 23] 
list_primes(32 36) -> [] 
```
​
## 12. Fibonacci Series
Write a function which takes a non-negative integer input named **n_iterations** and prints the corresponding [Fibonacci sequence](https://en.wikipedia.org/wiki/Fibonacci_number).  

Fibonacci numbers are a sequence of numbers such that each one is the sum of two preceding ones.  
Starting from **F(0) = 0** and **F(1) = 1**, following numbers are calculated according to  
**F(n)= F(n-1) + F(n-2) **  
where n >= 2. 

**Example:**   
```
fibonacci(5) -> 0 1 1 2 3
fibonacci(10) -> 0 1 1 2 3 5 8 13 21 34
```
​
## 13. Pascal Triangle 
Write a function which takes a non-negative integer input **n_rows** and prints the corresponding [Pascal Triangle](https://en.wikipedia.org/wiki/Pascal%27s_triangle). 

Pascal's triangle is a triangular arrangement of numbers that gives the coefficients in the expansion of binomial expression, such as (x+y)^n.  [See example](https://www.onlinemathlearning.com/image-files/pascals-triangle.png). It is constructed from the top to bottom, by summing the two numbers just above to the left and right of each position in the triangle. 

For simplicity, you don't need to care about the shape, you can print the triangle as below.

**Example:** 
```
pascal_triangle(5) -> 
1
1 1
1 2 1
1 3 3 1
1 4 6 4 1
```