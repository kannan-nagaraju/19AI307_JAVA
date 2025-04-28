# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
Write a Java program that keeps a number from the user and generates Name  for the given number between 0 and 9 and displays the name of the Number. 

## ALGORITHM :
1.	Start

2. Prompt the user to enter a number between 0 and 9

3. Read the number

4. Use a switch statement or if-else to match the number to its word

5. Display the name of the number

6. If the number is not between 0 and 9, show an error

7. End





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by:KANNAN N
RegisterNumber: 212223230097
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class NumberName {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("");
        int number = scanner.nextInt();
        scanner.close();

        if (number >= 0 && number <= 9) {
            String name = getNumberName(number);
            System.out.println("" + name);
        } else {
            System.out.println("Invalid range");
        }
    }

    public static String getNumberName(int number) {
        switch (number) {
            case 0:
                return "Zero";
            case 1:
                return "One";
            case 2:
                return "Two";
            case 3:
                return "Three";
            case 4:
                return "Four";
            case 5:
                return "Five";
            case 6:
                return "Six";
            case 7:
                return "Seven";
            case 8:
                return "Eight";
            case 9:
                return "Nine";
            default:
                return "Invalid Number";
        }
    }
}
```

## OUTPUT:

![Screenshot 2025-04-25 155702](https://github.com/user-attachments/assets/3074727f-2bbc-46b8-9d43-c8f9b8dfed06)


## RESULT:
Thus, The program accurately converts a digit to its word representation.

