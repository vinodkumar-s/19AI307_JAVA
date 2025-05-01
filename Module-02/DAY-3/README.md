# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To develop a Java Program to sort the elements of an array in ascending order.

## ALGORITHM :

1. Start the program and read the length of the array.
2. Declare an integer array of the given length.
3. Use a loop to read elements into the array from the user.
4. Sort the array using the `Arrays.sort()` method.
5. Print the sorted array elements.

## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: VINOD KUMAR S
RegisterNumber: 212222401116 
*/
```
## Sourcecode.java:
``` JAVA
import java.util.*;
public class Main{
    public static void main(String args[]){
        Scanner scan = new Scanner(System.in);
        int len = scan.nextInt();
        int  arr[] = new int[len];
        for(int ind = 0;ind<len;ind++){
            arr[ind] = scan.nextInt();
        }
         
         Arrays.sort(arr);
         System.out.println("Result of a Sorted Array :");
        for(int ind=0;ind<len;ind++){
            System.out.print(arr[ind]+"  ");
        }
    }
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/e35d4fca-be1d-4a0c-9cea-298ed647683b)

## RESULT:
Thus, the Java program Thus the java program to to sort the elements of an array in ascending order  was executed successfully.


