# Ex.No:1(A) CLASS & OBJECTS

## AIM:
Create a class named 'Distance' to add two distances in inch-feet by using third object.

## ALGORITHM :
1.	Start
2. Create a class Distance with:
   Data members: feet and inches Methods:

   a. get_distance() – to input values

   b. add_distance(d1, d2) – to add two Distance objects and store in the third

   c. display() – to display the result
4. Create three objects: d1, d2, and d3
5. Use d1.get_distance() and d2.get_distance() to get input
6. Call d3.add_distance(d1, d2)
7. Call d3.display()
8. End


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
import java.util.*;
public class Distance
{
    Float feet,inches;
    public static void main(String[] args)
    {
        Distance obj1=new  Distance();
        Distance obj2=new  Distance();
        Distance obj3=new  Distance();
        Scanner sc =new Scanner(System.in);
 
        obj1.feet=sc.nextFloat();
        obj1.inches=sc.nextFloat();
        obj2.feet=sc.nextFloat();
        obj2.inches=sc.nextFloat();
        
        obj3.feet=(obj1.feet+obj2.feet);
        obj3.inches=(obj1.inches+obj2.inches);
        System.out.println("Total Distance is "+obj3.feet+" feet and "+obj3.inches+" inches");
    }
}
```

## OUTPUT:
![Screenshot 2025-04-25 153756](https://github.com/user-attachments/assets/ab71fd7e-3a77-4303-afcc-92a784fb798d)



## RESULT:
The program successfully adds two distances in feet and inches using a third object and displays the correct total distance after converting inches to feet where necessary.
