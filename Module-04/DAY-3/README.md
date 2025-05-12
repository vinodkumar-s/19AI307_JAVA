# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a class named 'Gadgets' which includes methods display(). [display() will print "I am a Gadget"]

Create a child class of 'Gadgets' named 'Laptop' and add a new overriding method named display() [display() will print "I am a Laptop"] and print(). [ print() calls both overriding and overridden methods]

Create a instance of Laptop class and invoke the print method using object.

## ALGORITHM :
1: Start

2: Define a class Gadgets

a. Create a method display()

b. Inside display(), print "I am a Gadget"

 3: Define a class Parrot that extends Gadgets

a. Override the display() method

b. Inside the overridden display(), print "I am a Laptop"

c. Create a new method print()

d. Inside print(), use super.display() to call the parent class (Gadgets) version of display()

 4: Define the Main class with main() method

a. Create an object obj of class Parrot

b. Call obj.display() → Executes Parrot class's display() method

c. Call obj.print() → Executes Parrot class's print() method, which in turn calls Gadgets class's display() method using super

5: End

## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: VINOD KUMAR S
RegisterNumber:212222240116
*/
```

## Sourcecode.java:
```

class Gadgets {

  //Write Your code Here
  void display()
  {
      System.out.println("I am a Gadget");
  }
}

class Parrot extends Gadgets {

//Write Your code Here  
void display()
{
    System.out.println("I am a Laptop");
}
void print()
{
    super.display();
}
  
}

public class Main {
  public static void main(String[] args) {
      
      //Write Your code Here
      Parrot obj=new Parrot();
      obj.display();
      obj.print();
  }
}
```

## OUTPUT:

![437531173-240c300f-e074-4f6e-ba85-ca586e2ca81c](https://github.com/user-attachments/assets/17f2f5a6-af36-4250-94a2-ba638db04fb8)


## RESULT:
Thus the java program for constructor chaining was executed successfully.
