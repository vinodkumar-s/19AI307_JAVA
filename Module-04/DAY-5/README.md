# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Laptop class given below that initializes the brand , price class field with the string "Apple" and 42500.75.

Call the getBrand() method in the main method of the Sample class and store the value of the brand in a variable, and print the value.

Call the getPrice() method in the main method of the Sample class and store the value of the price in a variable, and print the value.

## ALGORITHM :

1.Start

2.Define class Laptop:

Declare a String variable brand.

Declare a double variable price.

Create a constructor Laptop():

Set brand to "Apple".

Set price to 42500.75.

3.Define a method getBrand():

Return the value of brand.

Define a method getPrice():

Return the value of price.

4.Define class Sample:

In the main method:

Create an object myLaptop of class Laptop.

Call getBrand() method using myLaptop and store the result in laptopBrand.
 
Print laptopBrand.
 
Call getPrice() method using myLaptop and store the result in laptopPrice.
 
Print laptopPrice.

5.End



## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by:VINOD KUMAR S
RegisterNumber: 212222240116
*/
```

## Sourcecode.java:
```
class Laptop {
    String brand;
    double price;
    public Laptop() {
        this.brand = "Apple";
        this.price = 42500.75;
    }

    public String getBrand() {
        return brand;
    }

    public double getPrice() {
        return price;
    }
}
public class Sample {
    public static void main(String[] args) {
        Laptop myLaptop = new Laptop();
        String laptopBrand = myLaptop.getBrand();
        System.out.println(laptopBrand);
        double laptopPrice = myLaptop.getPrice();
        System.out.println(laptopPrice);
    }
}
```

## OUTPUT:
![438026835-dd258499-d8e9-427a-97a0-9157d4055a30](https://github.com/user-attachments/assets/eec7963a-b392-4d04-a295-2bccf8d15763)

## RESULT:
Thus, the java program was successfully parameterized constructor in the Laptop class given below that initializes the brand , price class field with the string "Apple" and 42500.75.
