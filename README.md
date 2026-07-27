# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
import random

print("Pseudo Random Number Generation")

n = int(input("Enter how many numbers: "))
low = int(input("Enter lower limit: "))
high = int(input("Enter upper limit: "))

numbers = []

for i in range(n):
    x = random.randint(low, high)
    numbers.append(x)

print("Generated Numbers:")
for i in numbers:
    print(i)

print("Maximum:", max(numbers))
print("Minimum:", min(numbers))
print("Average:", sum(numbers) / len(numbers))
```
# OUTPUT:
<img width="1493" height="482" alt="image" src="https://github.com/user-attachments/assets/58c54aa4-e0de-4f9e-a9db-6fb56742e234" />

# RESULT:
Thus the python program is successfully created and verified.
