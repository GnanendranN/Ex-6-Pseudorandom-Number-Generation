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
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d\n", random_number);
    }
    return 0;
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/a92df70c-ebc9-47f1-a3d0-a1a1f1d43c01)

## RESULT:
Thus the program to execute a python program for Implementation of Pseudorandom Number Generation Using Standard library is successful
