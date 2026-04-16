# FizzBuzz

## What is this project?

This project contains a Java program called `FizzBuzz`. The program is designed to print out numbers from 1 to 100 (inclusive). However, instead of printing the number itself in certain cases, it prints specific words based on divisibility rules:

- If the number is divisible by 3, it prints "Fizz" instead of the number.
- If the number is divisible by 5, it prints "Buzz" instead of the number.
- If the number is divisible by both 3 and 5 (i.e., divisible by 15), it prints "FizzBuzz" instead of the number.
- Otherwise, it simply prints the number.

This is a classic programming exercise often used in coding interviews to test basic programming skills, such as loops and conditional statements.

### How the program works

The program is written in Java and consists of a single class with a `main` method. Here's a step-by-step explanation of the code:

1. **Loop Structure**: The program uses a `for` loop to iterate through each integer from 1 to 100.
   ```java
   for (int i = 1; i <= 100; i++) {
   ```

2. **Conditional Checks**: For each number `i`, the program checks conditions in order:
   - First, it checks if `i` is divisible by both 3 and 5 using `i % 3 == 0 && i % 5 == 0`. If true, it prints "FizzBuzz".
   - If not, it checks if `i` is divisible by 3 using `i % 3 == 0`. If true, it prints "Fizz".
   - If not, it checks if `i` is divisible by 5 using `i % 5 == 0`. If true, it prints "Buzz".
   - If none of the above, it prints the number `i`.

3. **Output**: Each check results in printing to the console using `System.out.println()`.

### Example Output
For the first 15 numbers, the output would be:
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```

This program demonstrates fundamental concepts in programming, including loops, conditionals, and modular arithmetic.

