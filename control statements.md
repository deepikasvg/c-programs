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
##  C PROGRAM TO FIND WHETHER A GIVEN YEAR IS A LEAP YEAR OR NOT
```
#include <stdio.h>

int main() {
    int year;

    // Input year
    printf("Enter a year: ");
    scanf("%d", &year);

    // Check leap year conditions
    if ((year % 400 == 0) || (year % 4 == 0 && year % 100 != 0)) {
        printf("%d is a Leap Year.\n", year);
    } else {
        printf("%d is NOT a Leap Year.\n", year);
    }

    return 0;
}
```
##  C PROGRAM TO READ THE AGE OF A CANDIDATE AND DETERMINE WHETHER HE IS ELIGIBLE TO CAST HIS/HER OWN VOTE
```
#include <stdio.h>

int main() {
    int age;

    // Input age
    printf("Enter your age: ");
    scanf("%d", &age);

    // Check voting eligibility
    if (age >= 18) {
        printf("You are eligible to cast your vote.\n");
    } else {
        printf("You are NOT eligible to cast your vote.\n");
    }

    return 0;
}
```
##  C PROGRAM TO READ THE VALUE OF AN INTEGER M AND DISPLAY THE VALUE OF N IS 1 WHEN M IS LARGER THAN 0, 0 WHEN M IS 0 AND -1 WHEN M IS LESS THAN 0
```
#include <stdio.h>

int main() {
    int m, n;

    printf("Enter an integer value for m: ");
    scanf("%d", &m);

    if (m > 0) {
        n = 1;
    } else if (m == 0) {
        n = 0;
    } else {
        n = -1;
    }
    printf("The value of n is: %d\n", n);

    return 0;
}
```
##  C PROGRAM TO FIND THE LARGEST OF THREE NUMBERS
```
#include <stdio.h>

int main() {
    int num1, num2, num3;

    printf("Enter three numbers: ");
    scanf("%d %d %d", &num1, &num2, &num3);

    if (num1 >= num2 && num1 >= num3) {
        printf("%d is the largest number.\n", num1);
    } 
    else if (num2 >= num1 && num2 >= num3) {
        printf("%d is the largest number.\n", num2);
    } 
    else {
        printf("%d is the largest number.\n", num3);
    }

    return 0;
}
```





