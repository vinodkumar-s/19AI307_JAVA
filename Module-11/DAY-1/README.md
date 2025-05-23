# Ex.No:11(A)         JAVA TREESET
## AIM:
 To develop a Java program to iterate through all elements in a tree set.


## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `TreeSet` named `set` to store integers in sorted order
4.	Use a loop to read `n` integers and add each to `set`
5.	Use an enhanced `for` loop to print each element in `set`
6.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
Developed by: VINOD KUMAR S
RegisterNumber: 212222240116
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Exercise2 {
  public static void main(String[] args) {
  Scanner sc=new Scanner(System.in);
  int size=sc.nextInt();
  TreeSet<Integer> tree_set = new TreeSet<Integer>();
  for(int i=0;i<size;i++)
  {
  tree_set.add(sc.nextInt());
  }
 
  for (Integer element : tree_set) {
    System.out.println(element);
    }
 }
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/8e05618e-4df4-4551-8910-3eaa8eb619f4)



## RESULT:
Thus the java program to iterate through all elements in a tree set was executed successfully.

