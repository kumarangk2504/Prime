# Prime
This Python script checks whether a given number is prime or not.

is_prime(number): This function takes an integer number as input and returns True if the number is prime, and False otherwise. It implements the optimized primality testing algorithm, which efficiently checks for divisibility up to the square root of the number.

if __name__ == "__main__":: This block of code ensures that the following code is only executed if the script is run directly (not imported as a module).

num = int(input("Enter a number to check if it's prime: ")): This line prompts the user to enter a number and converts the input to an integer.

if is_prime(num):: This line calls the is_prime function with the user-provided number and checks if it returns True (indicating that the number is prime) or False (indicating that the number is not prime).

Depending on the result, it prints either "<number> is a prime number." or "<number> is not a prime number."

When you run this script, it will ask you to enter a number, then it will determine whether the number is prime or not and print the result accordingly.
