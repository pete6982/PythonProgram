# PythonProgram

Use what you learn in the examples to write code in "StandardDeviation" that will calculate the sample standard deviation of a list of numbers. Copy and paste each example to the programiz compiler and play around with it.

To test your code, copy and paste your code to 
  https://www.programiz.com/python-programming/online-compiler/
Do not be discouraged! the best way to learn to code is by writing more code. Make changes and see what happens when you press "Run"

For info on the sample standard deviation:
https://www.google.com/search?q=sample+standard+deviation+formula

To calculate the sample standard deviation, you will need to calculate the sum of squared differences. The difference being an observation minus the mean (or average). To square the difference, just multiply the difference by itself. Using a loop, you can sum (or add) the squared differences just like you added the observations to get the total in the average() function. In that same loop, you can count the observations as in the average() function. You then divide the sum of squared differences by one less than the count of observations (i.e., n-1 or the degrees of freedom). You now have the sample variance. The square root of the sample variance is the sample standard deviation.

For example, if the list of numbers is {1, 2, 6}

The observations are 1, 2, and 6. There are 3 observations (count = 3 or n = 3).

The average would be
(1 + 2 + 6) / 3 = 3

The differences (observation minus the average) would be
1 - 3 = -2, 
2 - 3 = -1, 
6 - 3 = 3

The squared differences would be
-2 * -2 = 4, 
-1 * -1 = 1, 
3 * 3 = 9

The sum of squared differences would be 
4 + 1 + 9 = 14

The degrees of freedom is 2 (degrees of freedom = n - 1 or one less than the count of observations)

The sample variance is the sum of squared differences divided by the degrees of freedom, 14 / 2 = 7

The sample standard deviation is the square root of the sample variance (square root of 7 in this case). In Python, we can calculate this using math.sqrt(7)

To learn more about Python, go to https://www.programiz.com/python-programming/first-program
