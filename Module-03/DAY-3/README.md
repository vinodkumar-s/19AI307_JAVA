# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program to read input and print length of the string in java and use stringbuilder.

## ALGORITHM :
1. Start
2.Initialize a Scanner object to read input from the user.
3.	Read a string input from the user and store it in a variable called input.
4.	Create a StringBuilder object using the input string.
5.Calculate the length of the string using the length() method of the StringBuilder.
6.	Display the message: "The size of the String is ", where is the calculated length.
7. Close the Scanner object to free system resources.
8. End





## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: VINOD KUMAR S
RegisterNumber:  212222240116
*/
```

## Sourcecode.java:

```
import java.util.Scanner;

public class StringLength {
    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner scanner = new Scanner(System.in);

        String input = scanner.nextLine();

        // Create a StringBuilder object with the input string
        StringBuilder sb = new StringBuilder(input);

        // Get the length of the string
        int length = sb.length();

        // Output the result
        System.out.println("The size of the String is " + length);

        // Close the scanner
        scanner.close();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/7f3c9eda-093a-45f0-abc8-9061360030c2)



## RESULT:
Thus the java program to read input and print length of the string in java and use stringbuilder was executed successfully.



