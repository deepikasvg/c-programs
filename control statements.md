## COMPARSION OF TWO INTEGERS AND CHECK WHETHER THEY ARE EQUAL OR NOT
```
#include <stdio.h>

int main() {
    int num1, num2;

    // Input two integers
    printf("Enter first integer: ");
    scanf("%d", &num1);

    printf("Enter second integer: ");
    scanf("%d", &num2);

    // Check if they are equal
    if (num1 == num2) {
        printf("Both integers are equal.\n");
    } else {
        printf("The integers are not equal.\n");
    }

    return 0;
}
```

##  PROGRAM TO CHECK WHETHER A GIVEN NUMBER IS EVEN OR ODD
```
#include <stdio.h>

int main() {
    int num;

    // Input number
    printf("Enter an integer: ");
    scanf("%d", &num);

    // Check if even or odd
    if (num % 2 == 0) {
        printf("%d is an even number.\n", num);
    } else {
        printf("%d is an odd number.\n", num);
    }

    return 0;
}
```
##  PROGRAM TO CHECK WHETHER A GIVEN NUMBER IS POSITIVE OR NEGATIVE
```
#include<stdio.h>

int main(){
int num;

printf("enter an integer: ");
scanf("%d", &num);

if(num > 0) {
printf(" num is positive.\n");
}
if else(num < 0) {
printf("num is negitive. \n");
} else {
printf("num is zero.");
}
}
```
