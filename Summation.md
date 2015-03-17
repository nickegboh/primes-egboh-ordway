A program that shows four primes that have a sum equal to any given integer.

# Introduction #

The Summation of four primes project takes in one natural number (i) from a file as input and then computes a set of four primes that have a sum equal to i for output.

Input

The input contains one integer number N (N<=10000000) in every line. This is the number you will have to express as a summation of four primes. Input is terminated by end of file.

Output

For each line of input there is one line of output, which contains four prime numbers according to the given condition. If the number cannot be expressed as a summation of four prime numbers print the line “Impossible.” in a single line. There can be multiple solutions. Any good solution will be accepted.

By the Goldbach Conjecture any even number greater than 8 will have two 2s with two other primes that will sum equal it's sum. Any odd number will have a 2 and a 3 in it's set of four primes that equal the number as a sum. By using Goldbach's conjecture of how any natural number greater than or equal to four can be made by the sum of two primes it is possible to make this algorithm.