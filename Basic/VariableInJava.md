A variable is the name given to a memory location. It is the basic unit of storage in a program.

- The value stored in a variable can be changed during program execution.
- A variable is only a name given to a memory location, all the operations done on the variable effects that memory location.
- In Java, all the variables must be declared before they can be used.

###Rules of declair variables

- A variable name can consist of Capital letters A-Z, lowercase letters a-z, digits 0-9, and two special characters such as underscore and dollar Sign.
- The first character must be a letter.
- Blank spaces cannot be used in variable names.
- Java keywords cannot be used as variable names.
- Variable names are case-sensitive.

####How to declare variables?
We can declare variables in java as follows:
[![Variables in Java](http://cdncontribute.geeksforgeeks.org/wp-content/uploads/Variables-in-Java.png)](http://cdncontribute.geeksforgeeks.org/wp-content/uploads/Variables-in-Java.png)**datatype**: Type of data that can be stored in this variable.
**variable_name**: Name given to the variable.
**value**: It is the initial value stored in the variable.

![Declaration and assignment statements](https://www.w3schools.in/wp-content/uploads/2015/03/Declaration-and-assignment-statements.png)

**Examples**:

```java
float simpleInterest; //Declaring float variable
int time = 10, speed = 20; //Declaring and Initializing integer variable
char var = 'h'; // Declaring and Initializing character variable
```

If variables are of the same type, they can be declared together, as follows: 

```java
datatype variable1, variable2, ..., variablen;

```

The variables are separated by commas. 

For example,

`int i, j, k;`// Declare i, j, and k as int variables

Variables often have initial values. You can declare a variable and initialize it in one step.

Consider, for instance, the following code:

`int count = 1;`

This is equivalent to the next two statements:

```java
int count;
count = 1;
```

 You can also use a shorthand form to declare and initialize variables of the same type

together. For example,

```java
int i = 1, j = 2;
```

>  A variable must be declared before it can be assigned a value. A variable declared in a method must be assigned a value before it can be used. Whenever possible, declare a variable and assign its initial value in one step. This will make the program easy to read and avoid programming errors.

### Variable Scope means - That limit, as far as the variable can be used.

In Java there are various types of variable scope:

- **Local variables**
- **Instance variables**
- **Class/Static variables**

####Local variables

A variable that is declared within the method that is called local variables. It is defined in method or other statements, such as defined and used within the cache block, and outside the block or method, the variable cannot be used.

####Instance variables

A non-static variable that is declared within the class but not in the method is called instance variable. Instance variables are related to a specific object; they can access class variables.

####Class/Static variables

A variable that is declared with static keyword in a class but not in the method is called static or class variable.

####Example

```java
class A {
 int amount = 100; //instance variable  
 static int pin = 2315; //static variable 

 public static void main(String[] args) {
  int age = 35; //local variable  
 }
}
```

Example:

```java
public class Example {
 int salary; // Instance Variable

 public void show() {
  int value = 2; // Local variable
  value = value + 10;
  System.out.println("The Value is : " + value);
  salary = 10000;
  System.out.println("The salary is : " + salary);
 }

 public static void main(String args[]) {
  Example eg = new Example();
  eg.show();
 }
}
```