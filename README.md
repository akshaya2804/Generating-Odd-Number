Odd Number Generator

Key Components
Class Definition

The odd_num class generates random odd numbers within the range of 10 to 30.
It contains:
num: A random integer variable.
Constraint (odd_numbers): Ensures that num is odd and lies between 10 and 30.
Verification Module

The verify module creates an object of the odd_num class and randomizes the num variable.

If successful, it displays the randomized value.

 It Works
 
Randomization

The odd_num class uses the randomize() function to generate a value that meets the odd_numbers constraint.
Constraint Logic

The constraint ensures that the value:
Is odd (num % 2 == 1).
Lies between 10 and 30 (num >= 10 and num <= 30).

Verification

The verify module checks if the randomization is successful.
If successful, it displays the value. Otherwise, it reports a failure.
