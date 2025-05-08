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

count = int(input("Enter the number of random numbers to generate: "))
min_val = int(input("Enter the minimum value: "))
max_val = int(input("Enter the maximum value: "))

print("Pseudorandom numbers:")
for _ in range(count):
    print(random.randint(min_val, max_val))
```
# OUTPUT:
![Screenshot 2025-04-22 184312](https://github.com/user-attachments/assets/138c1db0-6715-47e7-88bf-5fc1082f7c23)


# RESULT:
The program is executed successfully.
