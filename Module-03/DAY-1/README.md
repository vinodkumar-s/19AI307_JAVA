# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.  Start the Program.
2.	Import `Scanner` and define class `demo`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a line of text into `String` variable `str`
4.	Print "The size of the String is " + `str.length()`
5.	End




## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: VINOD KUMAR S
RegisterNumber:  212222240116
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Main {
	public static void main(String[] args)
	{
    	// Here str is a string object
   	Scanner sc = new Scanner(System.in);  // Create a Scanner object
   	String str = sc.nextLine();

 
    	System.out.println(
        	"The size of "
        	+ "the String is "
        	+ str.length());
	}
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/d2482fa8-2f30-4a0f-bc40-8aba00e8a1eb)




## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.

