# integer-calculator
Calculator for number theory. Can:
- divide two numbers with a quotient and remainder
- find the greatest common denominator or lowest common multiple of two numbers
- find a number's prime factors
- generate a list of prime numbers

Can handle arbitrarily large numbers (yay python!), but it uses its primes list for some of the 
functions, so you have to regenerate it if you want to use a big number for those. (I'd suggest
keeping it small if you're not working with huge numbers as a very long primes list can slow it
down.)

Also I mainly wrote this so I could call it in a bash terminal, so it has a line at the top to 
tell bash to read it in python. Not sure if that'll cause problems on other computers, and if 
you want to call it with bash you may have to change that line; the path isn't universal.
