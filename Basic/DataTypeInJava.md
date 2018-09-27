

## Overview

This tutotial will talk about data type in Java programming language.

In [computer science](https://en.wikipedia.org/wiki/Computer_science) and [computer programming](https://en.wikipedia.org/wiki/Computer_programming), a **data type** or simply **type** is a classification of [data](https://en.wikipedia.org/wiki/Data) which tells the [compiler](https://en.wikipedia.org/wiki/Compiler) or [interpreter](https://en.wikipedia.org/wiki/Interpreter_(computing)) how the programmer intends to use the data.

In Java Programming language there are two types of data:

* Primitive data type
* Non-primitive data type

![Java Data Types](https://www.javatpoint.com/images/java-data-types.png)



##Primitive data type

There are 8 types of primitive data types:

- boolean data type
- byte data type
- char data type
- short data type
- int data type
- long data type
- float data type
- double data type



| **Data Type** | **Default Value** | **Default size** |
| ------------- | ----------------- | ---------------- |
| boolean       | false             | 1 bit            |
| char          | '\u0000'          | 2 byte           |
| byte          | 0                 | 1 byte           |
| short         | 0                 | 2 byte           |
| int           | 0                 | 4 byte           |
| long          | 0L                | 8 byte           |
| float         | 0.0f              | 4 byte           |
| double        | 0.0d              | 8 byte           |

## Non-primitive Datatypes

- Reference variables are created using defined constructors of the classes. They are used to access objects. These variables are declared to be of a specific type that cannot be changed. For example, Employee, Puppy, etc.
- Class objects and various type of array variables come under reference datatype.
- Default value of any reference variable is null.
- A reference variable can be used to refer any object of the declared type or any compatible type.
- Example: Animal animal = new Animal("giraffe");