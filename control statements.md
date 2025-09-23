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
