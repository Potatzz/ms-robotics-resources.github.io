# Code Library


This page contains useful code as well as basic java grammar for programming your robot.

Any code you write in java always lives inside a class. The file name must match the class name. 

public class HelloWorld {  
    public static void main(String[] args) {  
        System.out.println("Hello, world!");  
    }  
}  

# Classes

A class is the basic unit of Java. You define one with the class keyword. The name should start with a capital letter, and the file name must match.

public class MyProgram {  
    // code goes here  
}  

# The Main Method

This is the starting point of every Java program. Without it, the code won’t run.

public → means it can be accessed from anywhere.

static → means it belongs to the class, not an object.

void → means it doesn’t return anything.

main(String[] args) → the special method that runs first.
publc class MyProgram {
  public static void main(String[] args) {
      // program starts here
  }
}
# Variables
Variables are very important in java and programming the robot, they will hold a lot of data required for the robot to run 
Java requires you to declare the type of data a variable will hold.

int → whole numbers

double → decimals

String → text

boolean → true/false

int age = 20;
double price = 9.99;
String name = "Alexander";
boolean isJavaFun = true;

# Conditionals

Use if and else to control decisions. The condition inside parentheses must be true/false.

if (height >= 5) {
    System.out.println("Tall");
} else {
    System.out.println("Short");
}

# Loops

Loops repeat code.

For loop runs a set number of times.

While loop repeats while a condition is true.

for (int i = 0; i < 5; i++) {
    System.out.println(i);
}

while (age < 25) {
    age++;
    //++ function just increases the age by 1
}

# Methods

Methods group reusable code. They have a return type, a name, and parentheses for parameters.

public static greet(int a, int b) {
    int c = a + b;
    return c;
}
//if you dont have a return add void to it

# Key Rules

Every statement ends with ;

{ } group blocks of code

main is required for execution

Types of variables must be declared
