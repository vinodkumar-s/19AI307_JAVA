# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that returns the sum of all the even values in a 2D array.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: VINOD KUMAR S
RegisterNumber: 21222240116
*/
```

## Sourcecode.java:

```JAVA
import java.util.Scanner;

public class SumOfEvens1 {
	private static Scanner sc;
	public static void main(String[] args) 
	{
		int Size, i, EvenSum = 0;
		sc = new Scanner(System.in);
	 
	
		Size = sc.nextInt();	
		
		int [] a = new int[Size];
		
		
		for (i = 0; i < Size; i++)
		{
			a[i] = sc.nextInt();
		}   

		for(i = 0; i < Size; i++)
		{
			if(a[i] % 2 == 0)
			{
				EvenSum = EvenSum + a[i]; 
			}
		}		
		System.out.println("The Sum of Even Numbers in this Array = " + EvenSum);
	}
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/3e4fda48-437f-4f56-ac43-ac91910aa8f6)
## RESULT:
Thus the java program that returns the sum of all the even values in a 2D array was executed successfully.


