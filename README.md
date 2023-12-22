## Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.


## FACTORS

The provided Python script appears to factorize numbers by finding two smaller numbers whose product is equal to the given input value. The script reads numbers from a file specified as a command-line argument (argv[1]) and prints the factorization for each number.

Here's a brief overview of the script's functionality:

~ The factorize function takes an integer (value) as input and prints a simple decomposition of the integer into two smaller numbers.
~ The script checks if the correct number of command-line arguments is provided. If not, it exits.
~ It attempts to open the file specified in the command-line argument and reads numbers from the file line by line.
~ For each number read from the file, it calls the factorize function to print its factorization.
~ The script handles exceptions but does not provide detailed error messages or explanations.

## RSA

The provided Python script seems to perform a similar function to the previous script. Here's an overview of its functionality:

~ The script defines a function fc that searches a file specified as a command-line argument (sys.argv[1]) for numbers and prints their factorization in the form n = p * q.
~ The script reads each number from the file, converts it to an integer, and checks if it is even. If the number is even, it prints the factorization immediately.
~ If the number is odd, the script iterates through odd numbers starting from 3 up to half of the number, checking for factors. If a factor is found, it prints the factorization and breaks out of the loop.
~ If no factor is found, it prints the number as the product of itself and 1.
~ The script catches IndexError exceptions (presumably to handle cases where the command-line argument is not provided) but does not provide detailed error messages.
~ The script calls the fc function to execute its functionality.
