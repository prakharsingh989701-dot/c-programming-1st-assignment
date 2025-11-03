Q1. What do you mean by arrays give one example of array and how you can declared an array?
Ans. #include <stdio.h>
int main() {
    int numbers[5] = {10, 20, 30, 40, 50}; 
    
    printf("Elements of array:\n");
    for(int i = 0; i < 5; i++) {
        printf("%d ", numbers[i]);
    }
    return 0;
}

Q2. What do you mean by functions? Write the types of functions and give one example in code of each type?
Ans. #include <stdio.h>
int main() {
    int num;
    printf("Enter a number: "); 
    scanf("%d", &num);         
    printf("You entered: %d", num);
    return 0;
}
User defined function Example
#include <stdio.h>
void greet() {      
    printf("Hello, Welcome to C Programming!");
}

int main() {
    greet();     
    return 0;
}

Q3. What do you mean by Pointers ? Write a code how you can initialise the pointer?
Ans. #include <stdio.h>
int main() {
    int a = 10;
    int *ptr;     
    ptr = &a;       
    
    printf("Value of a: %d\n", a);
    printf("Address of a: %p\n", &a);
    printf("Value of pointer ptr: %p\n", ptr);
    printf("Value pointed by ptr: %d\n", *ptr);
    return 0;
}

Q4. What are the types of array? Write in a code 1D & 2D included?
Ans. #include <stdio.h>
int main() {
    // 1D Array Example
    int marks[3] = {85, 90, 95};
    printf("1D Array elements:\n");
    for(int i = 0; i < 3; i++) {
        printf("%d ", marks[i]);
    }

    // 2D Array Example
    int matrix[2][2] = {{1, 2}, {3, 4}};
    printf("\n\n2D Array elements:\n");
    for(int i = 0; i < 2; i++) {
        for(int j = 0; j < 2; j++) {
            printf("%d ", matrix[i][j]);
        }
        printf("\n");
    }
    return 0;
}

Q5. Explain the types of Operators in code?
Ans. #include <stdio.h>
int main() {
    int a = 10, b = 5;

    // Arithmetic Operators
    printf("Addition: %d\n", a + b);
    printf("Subtraction: %d\n", a - b);

    // Relational Operators
    printf("Is a greater than b? %d\n", a > b);

    // Logical Operators
    printf("Logical AND (a>5 && b<10): %d\n", (a > 5 && b < 10));

    // Assignment Operators
    a += 5;  // same as a = a + 5
    printf("After a += 5, a = %d\n", a);

    // Increment/Decrement Operators
    a++;
    b--;
    printf("After increment a=%d, after decrement b=%d\n", a, b);

    return 0;
}


