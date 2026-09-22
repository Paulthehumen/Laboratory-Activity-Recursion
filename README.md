# Laboratory Activity: Recursion

## Description
A Java program that calculates the Greatest Common Divisor (GCD) of two non-negative integers using recursion, based on the Euclidean algorithm: gcd(a, b) = gcd(b, a % b). The program also prints a trace of each recursive call as it runs.

## Programming Language
Java

## How to Compile and Run
1. Compile: `javac GcdRecursion.java`
2. Run: `java GcdRecursion`
3. Enter two non-negative integers when prompted (not both zero).

## Sample Input and Output
Input: a = 48, b = 18

Output:
gcd(48, 18) a % b = 12 -> next call: gcd(18, 12)
gcd(18, 12) a % b = 6 -> next call: gcd(12, 6)
gcd(12, 6) a % b = 0 -> next call: gcd(6, 0)
gcd(6, 0) -> base case reached, returns 6

The GCD of 48 and 18 is 6

## AI Disclosure
Claude (Anthropic AI) was used to help design the recursive function structure and add the execution trace print statements.
