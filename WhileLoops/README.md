# While Loops Practice Projects

## 1

There are several techniques for implementing the sqrt method in the Math class. One such technique is known as the Babylonian method. It approximates the square root of a number, n, by repeatedly performing a calculation using the following formula:

`nextGuess = (lastGuess + n / lastGuess) / 2`

When nextGuess and lastGuess are almost identical, nextGuess is the approximated square root. The initial guess can be any positive value (e.g., 1). This value will be the starting value for lastGuess. If the difference between nextGuess and lastGuess is less than a very small number, such as 0.0001, you can claim that nextGuess is the approximated square root of n. If not, nextGuess becomes lastGuess and the approximation process continues. 

### Specifications

* You do not need to create a second class, but you should implement the following method that returns the square root of n. This method must use a `while` loop.

`public static double sqrt(double n)`

* Your program should not allow inputs smaller than 0 and the user should be able to run the program as many times as they want. Use `while` loops to achieve this functionality.

#### Sample Outputs
```
Enter a nonnegative number to get the square root: 2
The square root of 2.0 is 1.4142480822406378 (actual: 1.4142135623730951)
Do you want to try another number (0 for no, 1 for yes)? 1

Enter a nonnegative number to get the square root: 17.5
The square root of 17.5 is 4.183300584955587 (actual: 4.183300132670378)
Do you want to try another number (0 for no, 1 for yes)? 0

Thanks for using the program.
```

```
Enter a nonnegative number to get the square root: -1
Invalid input. Please enter a nonnegative number: -22
Invalid input. Please enter a nonnegative number: 22
The square root of 22.0 is 4.690415826527849 (actual: 4.69041575982343)
Do you want to try another number (0 for no, 1 for yes)? 1

Enter a nonnegative number to get the square root: 1
The square root of 1.0 is 1.000000225070373 (actual: 1.0)
Do you want to try another number (0 for no, 1 for yes)? 1

Enter a nonnegative number to get the square root: 23
The square root of 23.0 is 4.795831568051202 (actual: 4.795831523312719)
Do you want to try another number (0 for no, 1 for yes)? 0

Thanks for using the program.
```

