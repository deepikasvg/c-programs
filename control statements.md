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
##  C PROGRAM TO CHECK WHETHER A CHARACTER IS A VOWEL OR CONSONANT
```
#include <stdio.h>

int main() {
    char ch;
    printf("Enter an alphabet: ");
    scanf("%c", &ch);
    if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u' ||
        ch == 'A' || ch == 'E' || ch == 'I' || ch == 'O' || ch == 'U') {
        printf("%c is a Vowel.\n", ch);
    } 
    else {
        if ((ch >= 'a' && ch <= 'z') || (ch >= 'A' && ch <= 'Z')) {
            printf("%c is a Consonant.\n", ch);
        } else {
            printf("%c is not an alphabet.\n", ch);
        }
    }

    return 0;
}
```
## C PROGRAM TO CHECK WHETHER A CHARACTER IS AN ALPHABET OR NOT
```
#include <stdio.h>

int main() {
    char ch;
    printf("Enter a character: ");
    scanf("%c", &ch);
    if ((ch >= 'a' && ch <= 'z') || (ch >= 'A' && ch <= 'Z')) {
        printf("%c is an Alphabet.\n", ch);
    } else {
        printf("%c is NOT an Alphabet.\n", ch);
    }

    return 0;
}
```
##  C PROGRAM TO FIND MINIMUM OR MAXIMUM BETWEEN TWO NUMBERS
```
#include <stdio.h>

int main() {
    int num1, num2;
    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);
    if (num1 > num2) {
        printf("Maximum = %d\n", num1);
        printf("Minimum = %d\n", num2);
    } else if (num2 > num1) {
        printf("Maximum = %d\n", num2);
        printf("Minimum = %d\n", num1);
    } else {
        printf("Both numbers are equal: %d\n", num1);
    }

    return 0;
}
```
## C PROGRAM TO ENTER WEEK NUMBER AND PRINT DAY OF WEEK
```
#include <stdio.h>

int main() {
    int week;
    printf("Enter week number (1-7): ");
    scanf("%d", &week);
    switch (week) {
        case 1:
            printf("Sunday\n");
            break;
        case 2:
            printf("Monday\n");
            break;
        case 3:
            printf("Tuesday\n");
            break;
        case 4:
            printf("Wednesday\n");
            break;
        case 5:
            printf("Thursday\n");
            break;
        case 6:
            printf("Friday\n");
            break;
        case 7:
            printf("Saturday\n");
            break;
        default:
            printf("Invalid week number! Please enter 1-7.\n");
    }

    return 0;
}
```
## C PROGRAM TO CHECK WHETHER A CHARACTER IS UPPERCASE OR LOWERCASE
```
#include <stdio.h>

int main() {
    char ch;
    printf("Enter a character: ");
    scanf("%c", &ch);
    if (ch >= 'A' && ch <= 'Z') {
        printf("%c is an Uppercase letter.\n", ch);
    }
    else if (ch >= 'a' && ch <= 'z') {
        printf("%c is a Lowercase letter.\n", ch);
    }
    else {
        printf("%c is not an alphabet character.\n", ch);
    }

    return 0;
}
```
##  C PROGRAM TO FIND NUMBER OF DAYS IN MONTH
```
#include <stdio.h>

int main() {
    int month;
    printf("Enter month number (1-12): ");
    scanf("%d", &month);

    switch(month) {
        case 1:  // January
        case 3:  // March
        case 5:  // May
        case 7:  // July
        case 8:  // August
        case 10: // October
        case 12: // December
            printf("Month %d has 31 days.\n", month);
            break;

        case 4:  // April
        case 6:  // June
        case 9:  // September
        case 11: // November
            printf("Month %d has 30 days.\n", month);
            break;

        case 2:  // February
            printf("Month %d has 28 or 29 days (leap year).\n", month);
            break;

        default:
            printf("Invalid month number! Please enter 1-12.\n");
    }

    return 0;
}
```
##  C PROGRAM TO FIND MAXIMUM BETWEEN TWO NUMBERS USING SWITCH CASE
```
 #include <stdio.h>

int main() {
    int num1, num2;
    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);
    switch (num1 > num2) {
        case 1: 
            printf("Maximum = %d\n", num1);
            break;

        case 0: 
            switch (num2 > num1) {
                case 1:
                    printf("Maximum = %d\n", num2);
                    break;
                case 0:
                    printf("Both numbers are equal: %d\n", num1);
                    break;
            }
            break;
    }

    return 0;
}
```
##  C PROGRAM TO PRINT EVEN NUMBERS BETWEEN 1 TO 20 USING A FOR LOOP
```
#include <stdio.h>

int main() {
    int i;

    printf("Even numbers between 1 to 20 are:\n");

    for (i = 1; i <= 20; i++) {
        if (i % 2 == 0) {   // check if number is even
            printf("%d ", i);
        }
    }

    return 0;
}
```
##  C PROGRAM TO CALCULATE THE SUM OF NUMBERS FROM 1 TO 100 USING A WHILE LOOP
```
#include <stdio.h>

int main() {
    int i = 1, sum = 0;

    while (i <= 100) {
        sum += i;   
        i++;        
    }

    printf("The sum of numbers from 1 to 100 is: %d\n", sum);

    return 0;
}
```
## A C PROGRAM TO FIND THE FACTORIAL OF A GIVEN NUMBER USING A FOR LOOP
```
#include <stdio.h>

int main() {
    int n, i;
    unsigned long long fact = 1;  
    printf("Enter a number: ");
    scanf("%d", &n);

    if (n < 0) {
        printf("Factorial is not defined for negative numbers.\n");
    } else {
        for (i = 1; i <= n; i++) {
            fact *= i;   
        }
        printf("Factorial of %d = %llu\n", n, fact);
    }

    return 0;
}
```
## C PROGRAM TO CHECK WHETHER A GIVEN NUMBER IS PRIME OR NOT USING A WHILE LOOP
```
#include <stdio.h>

int main() {
    int num, i = 2, isPrime = 1;

    printf("Enter a positive integer: ");
    scanf("%d", &num);

    if (num <= 1) {
        isPrime = 0; 
    } else {
        while (i <= num / 2) {
            if (num % i == 0) {
                isPrime = 0; 
                break;
            }
            i++;
        }
    }

    if (isPrime)
        printf("%d is a prime number.\n", num);
    else
        printf("%d is not a prime number.\n", num);

    return 0;
}
```
##  C PROGRAM TO FIND THE SUM OF DIGITS OF A NUMBER USING A WHILE LOOP
```
#include <stdio.h>

int main() {
    int num, digit, sum = 0;

    printf("Enter a number: ");
    scanf("%d", &num);

    while (num != 0) {
        digit = num % 10;   
        sum += digit;       
        num /= 10;          
    }

    printf("Sum of digits = %d\n", sum);

    return 0;
}
```
##  C PROGRAM TO PRINT FIBONACCI SERIES UP TO N TERMS USING A FOR LOOP
```
#include <stdio.h>

int main() {
    int n, first = 0, second = 1, next;

    printf("Enter the number of terms: ");
    scanf("%d", &n);

    printf("Fibonacci Series up to %d terms:\n", n);

    for (int i = 0; i < n; i++) {
        if (i <= 1)
            next = i;
        else {
            next = first + second;
            first = second;
            second = next;
        }
        printf("%d ", next);
    }

    return 0;
}
```
##  C PROGRAM TO REVERSE A GIVEN NUMBER USING A WHILE LOOP
```
#include <stdio.h>

int main() {
    int num, reversed = 0, remainder;

    printf("Enter an integer: ");
    scanf("%d", &num);

    while (num != 0) {
        remainder = num % 10;           
        reversed = reversed * 10 + remainder; 
        num = num / 10;                 
    }

    printf("Reversed number: %d\n", reversed);

    return 0;
}
```
##  C PROGRAM TO FIND THE LARGEST ELEMENT IN AN ARRAY USING A FOR LOOP
```
#include <stdio.h>

int main() {
    int n;

    printf("Enter the number of elements in the array: ");
    scanf("%d", &n);

    int arr[n];

    printf("Enter %d elements:\n", n);
    for (int i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }

    int max = arr[0]; 

    for (int i = 1; i < n; i++) {
        if (arr[i] > max) {
            max = arr[i]; 
        }
    }

    printf("The largest element in the array is: %d\n", max);

    return 0;
}
```
##  C PROGRAM TO FIND THE SMALLEST ELEMENT IN AN ARRAY USING A WHILE LOOP
```
#include <stdio.h>

int main() {
    int n, i = 1;

    printf("Enter the number of elements in the array: ");
    scanf("%d", &n);

    int arr[n];

    printf("Enter %d elements:\n", n);
    for (int j = 0; j < n; j++) {
        scanf("%d", &arr[j]);
    }

    int min = arr[0]; 

    while (i < n) {
        if (arr[i] < min) {
            min = arr[i]; 
        }
        i++;
    }

    printf("The smallest element in the array is: %d\n", min);

    return 0;
}
```

















