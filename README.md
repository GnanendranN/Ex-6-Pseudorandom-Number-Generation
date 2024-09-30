# Ex-6-Pseudorandom-Number-Generation
## Aim:
To write a python program for Implementation of Pseudorandom Number Generation Using Standard library
## ALGORITHM:
1. Import the Random Module
2. Generate a Random Integer
3. Generate a Random Floating-point Number
4. Choose a Random Element from a Sequence
5. Generate a Random Number Using Gaussian Distribution
## PROGRAM:
```
import random
random_int = random.randint(1, 100)
print(f"Random Integer: {random_int}")
random_float = random.random()
print(f"Random Float (0 to 1): {random_float}")
random_uniform = random.uniform(1.5, 10.5)
print(f"Random Float (1.5 to 10.5): {random_uniform}")
choices = ['apple', 'banana', 'cherry', 'date']
random_choice = random.choice(choices)
print(f"Random Choice: {random_choice}")
random.shuffle(choices)
print(f"Shuffled List: {choices}")
random_sample = random.sample(choices, 3)
print(f"Random Sample: {random_sample}")
random_gauss = random.gauss(0, 1)  # mean = 0, standard deviation = 1
print(f"Random Gaussian Value: {random_gauss}")
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/0bf3f311-830e-4e2e-bf89-068a5811e7b2)

## RESULT:
Thus the program to execute a python program for Implementation of Pseudorandom Number Generation Using Standard library is successful
