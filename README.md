# JS-Intermediate-Algorithm-Scripting
1. Convert the characters &, <, >, " (double quote), and ' (apostrophe), in a string to their corresponding HTML entities.
2. Compare two arrays and return a new array with any items only found in one of the two given arrays, but not both. In other words, return the symmetric difference of the two arrays.
   Note: You can return the array with its elements in any order.
3. Pairs of DNA strands consist of nucleobase pairs. Base pairs are represented by the characters AT and CG, which form building blocks of the DNA double helix.
   The DNA strand is missing the pairing element. Write a function to match the missing base pairs for the provided DNA strand. For each character in the provided string, find the base pair character. Return the results as a 2d array.
   For example, for the input GCG, return [["G", "C"], ["C","G"], ["G", "C"]]
   The character and its pair are paired up in an array, and all the arrays are grouped into one encapsulating array.
4. Find the missing letter in the passed letter range and return it.
   If all letters are present in the range, return undefined.
5. Return true if the given string is a palindrome. Otherwise, return false.
   A palindrome is a word or sentence that's spelled the same way both forward and backward, ignoring punctuation, case, and spacing.
   Note: You'll need to remove all non-alphanumeric characters (punctuation, spaces and symbols) and turn everything into the same case (lower or upper case) in order to check for palindromes.
   We'll pass strings with varying formats, such as racecar, RaceCar, and race CAR among others.
   We'll also pass strings with special symbols, such as 2A3*3a2, 2A3 3a2, and 2_A3*3#A2.
6. Perform a search and replace on the sentence using the arguments provided and return the new sentence.
   First argument is the sentence to perform the search and replace on.
   Second argument is the word that you will be replacing (before).
   Third argument is what you will be replacing the second argument with (after).
   Note: Preserve the case of the first character in the original word when you are replacing it. For example if you mean to replace the word Book with the word dog, it should be replaced as Dog
7. You will be provided with an initial array (the first argument in the destroyer function), followed by one or more arguments. Remove all elements from the initial array that are of the same value as these arguments.
   Note: You have to use the arguments object.
8. Find the smallest common multiple of the provided parameters that can be evenly divided by both, as well as by all sequential numbers in the range between these parameters.
   The range will be an array of two numbers that will not necessarily be in numerical order.
   For example, if given 1 and 3, find the smallest common multiple of both 1 and 3 that is also evenly divisible by all numbers between 1 and 3. The answer here would be 6.
9. Write a function that takes two or more arrays and returns a new array of unique values in the order of the original provided arrays.
   In other words, all values present from all arrays should be included in their original order, but with no duplicates in the final array.
   The unique numbers should be sorted by their original order, but the final array should not be sorted in numerical order.
   Check the assertion tests for examples.
10. Convert a string to spinal case. Spinal case is all-lowercase-words-joined-by-dashes.
11. We'll pass you an array of two numbers. Return the sum of those two numbers plus the sum of all the numbers between them. The lowest number will not always come first.
    For example, sumAll([4,1]) should return 10 because sum of all the numbers between 1 and 4 (both inclusive) is 10.
12. Given a positive integer num, return the sum of all odd Fibonacci numbers that are less than or equal to num.
    The first two numbers in the Fibonacci sequence are 1 and 1. Every additional number in the sequence is the sum of the two previous numbers. The first six numbers of the Fibonacci sequence are 1, 1, 2, 3, 5 and 8.
    For example, sumFibs(10) should return 10 because all odd Fibonacci numbers less than or equal to 10 are 1, 1, 3, and 5.
13. A prime number is a whole number greater than 1 with exactly two divisors: 1 and itself. For example, 2 is a prime number because it is only divisible by 1 and 2. In contrast, 4 is not prime since it is divisible by 1, 2 and 4.
    Rewrite sumPrimes so it returns the sum of all prime numbers that are less than or equal to num.
