####**What is a Operators ?**
=> Operators in computer programming are symbols or keywords that are used to perform specific operations or calculations on data. They are fundamental components of programming languages and are used to manipulate variables, values, and expressions. Operators allow you to perform tasks like addition, subtraction, comparison, and logical operations in your code. There are various types of operators, including:

**1. Arithmetic Operators:**

- Addition (+)
    ```java
    int a = 10 + 20;
    ```
- Subtraction (-)
    ```java
    int a = 20 - 10;
    ```
- Multiplication (*)
    ```java
    int m = 10 * 10;
    ```
- Division (/)
    ```java
    int d = 100 / 10;
    ```
- Modulus (%): Returns the remainder of a division operation.
    ```java
    int d = 100 % 10;
    ```
- Increment (++) and Decrement (--): Used to increase or decrease the value of a variable by 1.
    ```java
    int a = 10;
    int b = 20;
    a++;
    b--;
    ```

**2. Comparison Operators:**

- Equal to (==)
    ```java
    int a = 10;
    int b = 10;
    if(a == b) {
        System.out.println("is equal.");
    }
    ```
- Not equal to (!=)
    ```java
    int a = 10;
    int b = 9;
    if(a != b) {
        System.out.println("not equal.");
    }
    ```
- Greater than (>)
    ```java
    int a = 20;
    int b = 10;
    if(a > b) {
        System.out.println("a is greater.");
    }
    ```
- Less than (<)
    ```java
    int a = 10;
    int b = 20;
    if(a < b) {
        System.out.println("a is less.");
    }
    ```
- Greater than or equal to (>=)
    ```java
    int a = 20;
    int b = 10;
    if(a >= b) {
        System.out.println("a is greater or equal.");
    }
    ```
- Less than or equal to (<=)
    ```java
    int a = 10;
    int b = 20;
    if(a <= b) {
        System.out.println("a is less or equal.");
    }
    ```

**3. Logical Operators:**

- AND (&&): Returns true if both operands are true.
    ```java
    int a = 10;
    int b = 20;
    int c = 10;
    int d = 20;
    if((a == c) && (b == d)) { // this codition return true
        System.out.println("true.");
    }
    ```
- OR (||): Returns true if at least one operand is true.
    ```java
    int a = 10;
    int b = 20;
    int c = 10;
    int d = 20;
    if((a == b) || (b == d)) { // this codition return true
        System.out.println("true.");
    }
    ```
- NOT (!): Returns the opposite boolean value of the operand.
    ```java
    int a = 10;
    int b = 20;
    if(!(a == b)) { // this codition return true
        System.out.println("true.");
    }
    ```

**4. Assignment Operators:**

- Assignment (=): Assigns a value to a variable.
    ```java
    int a = 10;
    int b = 20;
    int c = 30;
    int d = 40;
    int n = a;
    ```
- Compound assignment operators (e.g., +=, -=, *=, /=): Perform an operation and assign the result to a variable in a single step.
    ```java
    int a = 10;
    a += 10;
    // result = 20;
    a -= 10;
    // result = 10;
    a *= 2;
    // result = 20;
    a /= 10;
    // result = 2;
    ```

**5. Bitwise Operators:**

- Bitwise AND (&)
    ```java
    int a = 9 & 8;
    ```
- Bitwise OR (|)
    ```java
    int a = 9 | 8;
    ```
- Bitwise XOR (^)
    ```java
    int a = 9 ^ 8;
    ```
- Bitwise NOT (~)
    ```java
    int a = 9 ~ 8;
    ```
- Left shift (<<)
    ```java
    int a = 9 << 1;
    ```
- Right shift (>>)
    ```java
    int a = 9 >> 1;
    ```

**6. Ternary Operator (Conditional Operator):**

- ``` condition ? true : false; ``` - Used to assign a value to a variable based on a condition. It's a concise way of writing if-else statements.
    ```java
    int a = 10;
    int b = 20;
    
    // checking which number is greater
    int ans = 10 > 20 ? a : b;
    
    System.out.println("ans: ", ans);
    // output : 20
    ```

**7. Membership Operators:**

- in: Checks if a value is present in a sequence (e.g., a list or a string).
- not in: Checks if a value is not present in a sequence.

**8. Identity Operators:**

- is: Checks if two variables reference the same object in memory.
- is not: Checks if two variables reference different objects in memory.