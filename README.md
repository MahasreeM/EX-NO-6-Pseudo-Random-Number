### REG.NO:212224110035
### DATE:13-09-2025
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
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n = 5 % 100;  
    int i;

    srand(time(0));
    printf("Generating %d random numbers:\n", n);
    for (i = 0; i < n; i++)
    {
        printf("%d ", rand());
    }

    printf("\n");
    return 0;
}

```
# OUTPUT:

<img width="751" height="212" alt="image" src="https://github.com/user-attachments/assets/9297446e-8089-4686-87f5-77710efc211c" />

# RESULT:

Thus the implemented to result was successfully verified.
