# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To write a Java program that creates an object of a class Student and assigns values to the data members roll_no and name, then prints them.



## ALGORITHM :
####  1 Define a class Student with two data members roll_no and name.
####  2 Create the main method inside the class.
####  3 Create an object of the Student class.
####  4 Assign the value 21CSE03 to roll_no using the object.
####  5 Assign the value John to name using the object.
####  6 Print roll_no and name.
####  7 End the program.

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

public static void main(String[] args)
{
    Student obj=new Student();
    obj.roll_no="21CSE03";
    obj.name="John";
    System.out.println(obj.roll_no+" "+obj.name);
}
```



## OUTPUT:
![image](https://github.com/user-attachments/assets/5e6221f6-d86b-4cf9-a4e5-68592a2f6b94)




## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
