# Introduction-to-java
##Day 1 

###Introduction to Java 

 

Java is a high-level, object-oriented programming language. 

Its known for its write once, run everywhere flexibility, meaning that the code written in java can run on any device that supports java without the need for recompilation. 

Java is a high-level, object-oriented programming language developed by Sun Microsystems (now owned by Oracle Corporation). It was first released in 1995 and has since become one of the most popular and widely used programming languages in the world. 

 

Key characteristics of Java include: 

 

1. Platform Independence: Java code can run on any device that has a Java Virtual Machine (JVM) installed, making it a "write once, run anywhere" language. 

 

2. Object-Oriented:  It is based on the concept of objects and classes, allowing developers to create modular and reusable code. 

 

3. Robust and Secure: Java incorporates strong memory management, exception handling, and a robust security model to create secure applications. 

 

4. Multi-threaded: It supports concurrent programming by enabling multiple threads to execute simultaneously, enhancing the performance of applications. 

 

5. Large Standard Library: Java comes with a vast standard library that provides numerous pre-built functionalities and tools for developers. 

 

Java is used in various domains, including web development, mobile application development (Android apps are predominantly built using Java), enterprise software, scientific applications, and more. 

 

 It is also the language behind many frameworks, such as Spring for enterprise applications, hibernate for database management, and others, making it a versatile language in the software development landscape. 

 

 

 

 

 

 

 

 

Java components  

 

 

Java comprises several components that together enable the development and execution of Java applications. Some of the key components of Java include: 

 

1. **Java Development Kit (JDK):** The JDK is a software development kit used to develop Java applications. It includes tools such as the Java compiler, Java Virtual Machine (JVM), libraries, debugger, and other utilities necessary for Java development. 

 

2. **Java Virtual Machine (JVM):** JVM is a crucial component of the Java Runtime Environment (JRE) responsible for executing Java bytecode. It provides a platform-independent execution environment by translating bytecode into machine-specific code at runtime. 

 

3. Java Runtime Environment (JRE): JRE includes the JVM along with libraries and other resources required to run Java applications. It doesn't contain development tools like the JDK but allows users to execute Java applications on their systems. 

 

4. Java Standard Edition (Java SE): It is the core Java platform used for developing general-purpose applications. Java SE includes the basic libraries, APIs, tools, and the runtime environment necessary for building and running Java applications. 

 

5. Java Enterprise Edition (Java EE): Java EE, now known as Jakarta EE, is a set of specifications, APIs, and runtime environments for developing enterprise-level applications. It provides tools and frameworks for building scalable, distributed, and robust applications. 

 

6. JavaFX: JavaFX is a platform for creating rich client applications using Java. It offers a set of graphics and media packages for building interactive applications with rich user interfaces across multiple platforms. 

 

7. Java Database Connectivity (JDBC): JDBC is an API that enables Java applications to interact with databases. It provides methods for executing SQL queries, retrieving and modifying data, and managing database connections. 

 

8. Java APIs and Libraries: Java includes a vast collection of standard APIs and libraries that offer functionalities for networking, input/output operations, GUI development, data structures, security, and more. These APIs simplify various tasks for developers and support diverse application development needs. 

 

These components collectively form the Java ecosystem, providing developers with the necessary tools, libraries, and environments to create a wide range of applications across different domains and platforms. 

 

 A typical structure of a Java program  

consists of several key components and follows a specific organization. Here's a breakdown of the typical structure of a Java program: 

  

1. Package Declaration (Optional): 

   - It is the first statement that can appear in a Java file and is optional. It defines a package to which the file belongs. 

   - Syntax example: `package com.example.myprogram;` 

  

2. Import Statements (Optional): 

   - Following the package declaration (if present), import statements can be used to import classes, interfaces, or entire packages from other packages. 

   - Syntax example: `import java.util.*;` or `import java.util.ArrayList;` 

  

3. Class Declaration: 

   - Every Java program needs at least one class declaration. The `public` class must have the same name as the file it's in. 

   - Syntax example: 

     ```java 

     public class MyClass { 

         // Class contents (fields, methods) 

     } 

     ``` 

  

4. Main Method: 

   - The `main()` method is the entry point of a Java program. It's where the program execution starts. 

   - Syntax example: 

     ```java 

     public static void main(String[] args) { 

         // Program logic and functionality 

     } 

     ``` 

  

5. Comments: 

   - Java allows single-line (`//`) and multi-line (`/* */`) comments. These are used for code documentation and explanation. 

   - Syntax example: 

     ```java 

     // This is a single-line comment 

  

     /* 

     This is a 

     multi-line comment 

     */ 

     ``` 

  

6.Variables and Data Types: 

   - Java supports various data types such as `int`, `double`, `boolean`, etc. Variables are declared using these data types. 

   - Syntax example: 

     ```java 

     int age = 25; 

     double temperature = 98.6; 

     boolean isStudent = true; 

     ``` 

  

7.Methods (Functions): 

   - Methods contain the behavior or functionality of the program. They can perform specific tasks and can be called from within the class or other classes. 

   - Syntax example: 

     ```java 

     public void displayMessage() { 

         System.out.println("Hello, world!"); 

     } 

     ``` 

  

8. Control Structures: 

   - Java includes various control structures like loops (`for`, `while`, `do-while`) and conditional statements (`if`, `else`, `switch`) to control the flow of execution in the program. 

  

9. Object-Oriented Concepts: 

   - Java is an object-oriented programming language. Concepts like classes, objects, inheritance, polymorphism, and encapsulation are fundamental to Java programming. 

  

10. Exception Handling (Optional): 

    - Java provides mechanisms to handle exceptions using `try`, `catch`, `finally`, and `throw` blocks to manage runtime errors gracefully. 

  

11. Closing Resources (Optional): 

    - If your program uses resources like files or network connections, it's good practice to close them properly using `close()` or `finally` block to release resources. 

  

Here's a basic example showcasing a typical Java program structure: 

  

```java 

package com.example.myprogram; 

  

import java.util.Scanner; 

  

public class MyClass { 

    public static void main(String[] args) { 

        // Program logic 

        System.out.println("Hello, world!"); 

    } 

  

    // Other methods, variables, and classes can be defined here 

} 

``` 

  

This structure serves as a foundation for Java programs, allowing developers to create robust and organized applications. 

 

##Day 2 

###Variables 

 a variable is a named storage location in the computer's memory that holds data that can be manipulated or changed during the execution of a program.  

Variables are used to store information such as numbers, text, or objects that the program needs to work with. 

  

Variables in Java have several characteristics: 

  

1. **Name:** A variable is identified by a name, which is used to refer to it within the program. Variable names must follow specific rules such as starting with a letter, underscore (_), or dollar sign ($) and can contain letters, digits, underscores, and dollar signs. 

  

2. **Data Type:** Every variable in Java has a data type that specifies the kind of data it can hold. Examples of data types include `int` (for integers), `double` (for floating-point numbers), `boolean` (for true/false values), `String` (for text), and many others. Java is a statically typed language, meaning the data type of a variable must be declared before the variable can be used. 

  

3. **Memory Location:** Variables reserve space in the computer's memory to store their values. The size of the memory allocated depends on the data type of the variable. 

  

4. **Value:** A variable can store and hold a value of its declared data type. The value can be changed during the execution of the program. 

  

Here are some examples of variable declarations in Java: 

  

```java 

int age; // Declaration of an integer variable named 'age' 

double temperature; // Declaration of a double variable named 'temperature' 

boolean isStudent; // Declaration of a boolean variable named 'isStudent' 

String name; // Declaration of a String variable named 'name' 

``` 

  

Variables can be assigned initial values upon declaration or later in the program: 

  

```java 

int numberOfStudents = 20; // Declaration and initialization of an integer variable 

temperature = 98.6; // Assigning a value to the 'temperature' variable 

name = "John Doe"; // Assigning a value to the 'name' variable 

``` 

  

It's important to note that variables in Java have a specific scope, which defines where in the program they can be accessed and used. The scope of a variable is typically within the block of code where it is declared. 

 

####Data type  

 

Defines the value that a variable can take,  

 

There's two categories of data types. 

 

Primitive data type  

A primitive data type specifies the size and type of variable values, and it has no additional methods. 

 

We have 8 primitive data types in java. 

Data Type 

Size 

Description 

byte 

1 byte 

Stores whole numbers from -128 to 127 

short 

2 bytes 

Stores whole numbers from -32,768 to 32,767 

int 

4 bytes 

Stores whole numbers from -2,147,483,648 to 2,147,483,647 

long 

8 bytes 

Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 

float 

4 bytes 

Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits 

double 

8 bytes 

Stores fractional numbers. Sufficient for storing 15 decimal digits 

boolean 

1 bit 

Stores true or false values 

char 

2 bytes 

Stores a single character/letter or ASCII values 

 

Non-primitive data type  

These are the datatypes which have instances like objects. Hence, they are called reference variables. They are primarily classes, arrays, strings or interfaces. 

They are 

String  

Array  

 

 

Operator's in java 

An operator is a character that represents an action. 

 

Java operators can be classified into: 

Arithmetic Operators 

Relational Operators 

Bitwise Operators 

Logical Operators 

Assignment Operators 

Misc Operators 

 

Arithmetic operators  

 

Arithmetic operators are used in mathematical expressions in the same way that they are used in algebra.  

The following table lists the arithmetic operators −Assume integer variable A holds 10 and variable B holds 20, then 

 

Operator 

Description 

Example 

+ (Addition) 

Adds values on either side of the operator. 

A + B will give 30 

- (Subtraction) 

Subtracts right-hand operand from left-hand operand. 

A - B will give -10 

* (Multiplication) 

Multiplies values on either side of the operator. 

A * B will give 200 

/ (Division) 

Divides left-hand operand by right-hand operand. 

B / A will give 2 

% (Modulus) 

Divides left-hand operand by right-hand operand and returns remainder. 

B % A will give 0 

++ (Increment) 

Increases the value of operand by 1. 

B++ gives 21 

-- (Decrement) 

Decreases the value of operand by 1. 

B-- gives 19 

Relational operators – the table below show the relational operators supported by java. 

  

Operator 

Description 

Example 

== (equal to) 

Checks if the values of two operands are equal or not, if yes then condition becomes true. 

(A == B) is not true. 

!= (not equal to) 

Checks if the values of two operands are equal or not, if values are not equal then condition becomes true. 

(A != B) is true. 

> (greater than) 

Checks if the value of left operand is greater than the value of right operand, if yes then condition becomes true. 

(A > B) is not true. 

< (less than) 

Checks if the value of left operand is less than the value of right operand, if yes then condition becomes true. 

(A < B) is true. 

>= (greater than or equal to) 

Checks if the value of left operand is greater than or equal to the value of right operand, if yes then condition becomes true. 

(A >= B) is not true. 

<= (less than or equal to) 

Checks if the value of left operand is less than or equal to the value of right operand, if yes then condition becomes true. 

(A <= B) is true. 

Bitwise operators – works on bits and performs bit-by-bit operation, assume if a = 60 and b = 13; now in binary format they will be as follows: 

a = 0011 1100 

b = 0000 1101 

a&b = 0000 1100 

a|b = 0011 1101 

a^b = 0011 0001 

~a = 1100 0011 

  

Operator 

Description 

Example 

& (bitwise and) 

Binary AND Operator copies a bit to the result if it exists in both operands. 

(A & B) will give 12 which is 0000 1100 

| (bitwise or) 

Binary OR Operator copies a bit if it exists in either operand. 

(A | B) will give 61 which is 0011 1101 

^ (bitwise XOR) 

Binary XOR Operator copies the bit if it is set in one operand but not both. 

(A ^ B) will give 49 which is 0011 0001 

~ (bitwise compliment) 

Binary Ones Complement Operator is unary and has the effect of 'flipping' bits. 

(~A) will give -61 which is 1100 0011 in 2's complement form due to a signed binary number. 

<< (left shift) 

Binary Left Shift Operator. The left operands value is moved left by the number of bits specified by the right operand. 

A << 2 will give 240 which is 1111 0000 

>> (right shift) 

Binary Right Shift Operator. The left operands value is moved right by the number of bits specified by the right operand. 

A >> 2 will give 15 which is 1111 

>>> (zero fill right shift) 

Shift right zero fill operator. The left operands value is moved right by the number of bits specified by the right operand and shifted values are filled up with zeros. 

A >>>2 will give 15 which is 0000 1111 

Logical operators - The following table lists the logical operators −Assume Boolean variables A holds true and variable B holds false, then: 

  

Operator 

Description 

Example 

&& (logical and) 

Called Logical AND operator. If both the operands are non-zero, then the condition becomes true. 

(A && B) is false 

|| (logical or) 

Called Logical OR Operator. If any of the two operands are non-zero, then the condition becomes true. 

(A || B) is true 

! (logical not) 

Called Logical NOT Operator. Use to reverses the logical state of its operand. If a condition is true then Logical NOT operator will make false. 

!(A && B) is true 

 

 

 

 

The Assignment Operator 

Following are the assignment operator supported by Java language − 

  

Operator 

Description 

Example 

= 

Simple assignment operator. Assigns values from right side operands to left side operand. 

C = A + B will assign value of A + B into C 

 

 

Java Classes and Objects 

 

A Class is like an object constructor, or a "blueprint” or a factory for creating objects. 

This means without a class no object can be created. 

What is a class in java 

A class can be defined as a template/blueprint that describes the behavior/state that the object of its type support. 

 

Creating a class  

To create a class, use the keyword class 

 

A class is made up of below 

Constructor - is a method called when creating an object from a class 

If we do not explicitly write a constructor for a class, the Java compiler builds a default constructor for that class.  

Some constructors may accept parameter, and some may not. 

 

 

 

Methods 

A class can have any number of methods to access the value of various kinds of methods.  

 

in the example given below run,  

walk and sleep are methods 

Variables/Properties 

Usually these are attributes the describe objects that a created from that class. In the below example name, age and height are variables 

Example of class: 

public class Car { 

    // Attributes or Fields 

    private String brand; 

    private String model; 

    private int year; 

    private double price; 

  

    // Constructor 

    public Car(String brand, String model, int year, double price) { 

        this.brand = brand; 

        this.model = model; 

        this.year = year; 

        this.price = price; 

    } 

  

    // Getters and Setters for the attributes 

    public String getBrand() { 

        return brand; 

    } 

  

    public void setBrand(String brand) { 

        this.brand = brand; 

    } 

  

    public String getModel() { 

        return model; 

    } 

  

    public void setModel(String model) { 

        this.model = model; 

    } 

  

    public int getYear() { 

        return year; 

    } 

  

    public void setYear(int year) { 

        this.year = year; 

    } 

  

    public double getPrice() { 

        return price; 

    } 

  

    public void setPrice(double price) { 

        this.price = price; 

    } 

  

    // Method to display car information 

    public void displayCarInfo() { 

        System.out.println("Car: " + brand + " " + model + " (" + year + ")"); 

        System.out.println("Price: $" + price); 

    } 

  

    // Main method to demonstrate the usage of the Car class 

    public static void main(String[] args) { 

        // Creating an instance of Car class 

        Car myCar = new Car("Toyota", "Camry", 2022, 25000.50); 

  

        // Using setter method to change the price 

        myCar.setPrice(27000.75); 

  

        // Displaying car information using displayCarInfo() method 

        myCar.displayCarInfo(); 

    } 

} 

 

 

 ##Day 3 

###OOP  

Certainly! Here's a rewritten version of the information about OOP, its advantages, core features, other features, and example Java classes: 

  

### What is OOP? 

  

Object-Oriented Programming (OOP) is a programming paradigm centered around the concept of "objects." Java, a widely used language, embodies OOP principles. 

  

### Key Concepts in Java OOP: 

  

1. **Class:** 

   - Blueprint or template defining attributes (fields) and behaviors (methods) of objects. 

  

2. **Object:** 

   - Instance of a class representing a specific entity in the program. 

  

3. **Method:** 

   - Function defined within a class representing object behaviors. 

  

4. **Instance Variable:** 

   - Variable defined in a class representing an object's state or properties. 

  

5. **Constructor:** 

   - Special method initializing objects upon creation, sharing the class's name. 

  

### Advantages of OOP: 

  

1. **Modularity and Reusability:** Encapsulation organizes code into self-contained modules for easy reuse. 

   

2. **Code Reusability:** Inheritance permits new classes to inherit properties and behaviors, reducing redundancy. 

   

3. **Abstraction:** Focuses on essential object properties, hiding unnecessary details. 

   

4. **Encapsulation:** Restricts access to certain components, minimizing complexity and improving maintainability. 

   

5. **Flexibility and Extensibility:** Polymorphism allows treating different objects as the same type, promoting generic code. 

   

6. **Modeling Real-World Concepts:** Aligns closely with real-world entities and relationships for effective modeling. 

   

7. **Collaborative Development:** Encourages well-defined interfaces, facilitating teamwork on different system parts. 

   

8. **GUI Development:** Suited for creating graphical user interfaces by representing visual elements as objects. 

  

### Core Features of OOP: 

  

1. **Encapsulation:** Bundles data and methods into a class. 

   

2. **Polymorphism:** Allows treating different types as a common type. 

   

3. **Inheritance:** Enables a class to inherit properties and behaviors from another class. 

   

4. **Abstraction:** Simplifies complex systems by focusing on essential object aspects. 

  

### Other Features Related to OOP: 

  

1. **Coupling:** Measures dependence between classes or modules. 

   

2. **Cohesion:** Measures relationships within modules. 

   

3. **Association:** Represents bidirectional relationships between classes. 

   

4. **Aggregation:** "Whole-part" relationship, allowing parts to exist independently. 

   

5. **Composition:** Stronger form of aggregation where parts cannot exist independently. 

  

### Activity 3: Example Java Classes: 

  

```java 

// PurchaseItem Class 

public class PurchaseItem { 

    private String name; 

    private double unitPrice; 

  

    public PurchaseItem(String name, double unitPrice) { 

        this.name = name; 

        this.unitPrice = unitPrice; 

    } 

  

    public double getPrice() { 

        return unitPrice; 

    } 

} 

  

// WeighedItem Class (Subclass of PurchaseItem) 

public class WeighedItem extends PurchaseItem { 

    private double weight; 

  

    public WeighedItem(String name, double unitPrice, double weight) { 

        super(name, unitPrice); 

        this.weight = weight; 

    } 

  

    @Override 

    public double getPrice() { 

        return super.getPrice() * weight; 

    } 

} 

  

// CountedItem Class (Subclass of PurchaseItem) 

public class CountedItem extends PurchaseItem { 

    private int quantity; 

  

    public CountedItem(String name, double unitPrice, int quantity) { 

        super(name, unitPrice); 

        this.quantity = quantity; 

    } 

  

    @Override 

    public double getPrice() { 

        return super.getPrice() * quantity; 

    } 

} 

  

// Usage example 

public class Main { 

    public static void main(String[] args) { 

        WeighedItem banana = new WeighedItem("Banana", 3.00, 1.37); 

        System.out.println(banana.getName() + " @ " + banana.getPrice()); 

  

        CountedItem pens = new CountedItem("Pens", 4.5, 10); 

        System.out.println(pens.getName() + " @ " + pens.getPrice()); 

    } 

} 

``` 

  

These classes demonstrate inheritance and overridden methods to calculate prices for weighed and counted items. 

  

### Additional OOP Concepts: 

  

1. **Coupling:** Degree of dependence between classes or modules. 

   

2. **Cohesion:** Level of relatedness within modules. 

   

3. **Association:** Bidirectional relationship between classes. 

   

4. **Aggregation:** "Whole-part" relationship allowing independent existence. 

   

5. **Composition:** Stronger "whole-part" relationship with dependent existence. 

 

Object-Oriented Programming (OOP) gained popularity over declarative and procedural programming paradigms due to several advantages it offers: 

  

1. **Modularity and Reusability:** 

   - OOP promotes encapsulation, bundling data and functionalities into objects. This modularity enables easier code organization, maintenance, and reuse. Objects can be reused in different parts of the code or in entirely different projects, enhancing efficiency and reducing redundancy. 

  

2. **Code Reusability through Inheritance:** 

   - Inheritance in OOP allows creating new classes based on existing ones, inheriting their attributes and behaviors. This feature minimizes redundant code, promotes code reuse, and helps build hierarchies of related classes. 

  

3. **Abstraction for Simplification:** 

   - OOP emphasizes abstraction, focusing on essential properties and hiding complex implementation details. This approach simplifies the understanding of code and enhances manageability by representing real-world entities as objects with specific behaviors and attributes. 

  

4. **Encapsulation for Better Control:** 

   - Encapsulation restricts access to certain components of an object, allowing developers to control and protect data integrity. By hiding implementation details, encapsulation reduces complexity, improves maintainability, and minimizes unintended interference with the internal workings of a class. 

  

5. **Flexibility and Extensibility through Polymorphism:** 

   - Polymorphism allows objects of different types to be treated as objects of a common type, enabling the creation of generic and flexible code. This feature facilitates the handling of different types uniformly and enhances the adaptability of code to changing requirements. 

  

6. **Modeling Real-World Concepts:** 

   - OOP aligns closely with how we conceptualize real-world entities and relationships, making it easier to map real-world problems into code. The concepts of objects, classes, inheritance, and relationships between objects resemble the relationships between real-world entities, making the code more intuitive and easier to design. 

  

7. **Collaborative Development:** 

   - OOP encourages the creation of well-defined interfaces between different parts of a program. This facilitates teamwork, as different developers can work on distinct modules or classes independently, as long as they adhere to the specified interfaces. 

  

8. **Suitability for GUI Development:** 

   - OOP aligns well with graphical user interface (GUI) development principles. Objects representing visual elements and their interactions in the GUI can be modeled effectively using OOP concepts. 

  

While declarative and procedural programming paradigms have their strengths, the advantages offered by OOP, such as code organization, reusability, abstraction, flexibility, and modeling capabilities, have contributed significantly to its popularity and widespread adoption in software development. 

OOP Core Features 

 

Encapsulation is when object only exposes selected information 

Inheritance one class acquires the methods and properties of another. 

Polymorphism Entities can have more than one form. 

Abstraction hides complex details to reduce complexity. 

 

The core features of Object-Oriented Programming (OOP)  

 

1. **Encapsulation:** 

   - Encapsulation is the bundling of data (attributes) and methods (functions) that operate on the data into a single unit known as a class. It allows the internal workings of an object to be hidden from the outside, providing controlled access to the object's state and behaviors. Encapsulation helps in data protection and promotes the principle of information hiding. 

  

2. **Polymorphism:** 

   - Polymorphism refers to the ability of objects to take on multiple forms. In Java, polymorphism allows objects of different classes to be treated as objects of a common superclass through inheritance. There are two main types of polymorphism: 

     - **Compile-time Polymorphism (Method Overloading):** It involves having multiple methods in the same class with the same name but different parameters. 

     - **Runtime Polymorphism (Method Overriding):** It allows a subclass to provide a specific implementation of a method that is already defined in its superclass.  

  

3. **Inheritance:** 

   - Inheritance is a mechanism that allows a class (subclass or derived class) to inherit properties (attributes and methods) and behaviors from another class (superclass or base class). The subclass can extend or override the functionalities of its superclass. It promotes code reuse, hierarchy establishment, and the creation of a more specialized class from a more generalized one. 

  

4. **Abstraction:** 

   - Abstraction involves simplifying complex systems by modeling classes based on the essential properties and behaviors relevant to the problem. It allows programmers to focus on what an object does rather than how it achieves its functionality. Abstract classes and interfaces are used to achieve abstraction in Java. Abstraction enables the creation of generalized blueprints that can be extended for more specific implementations. 

  

These core features provide the foundation for designing and implementing object-oriented systems.  

They enable developers to create modular, reusable, and maintainable code by promoting concepts such as code organization, data protection, code reuse, and flexibility in handling various object interactions and hierarchies. 

 

Features of OOP – Other features 

 

Besides the core features of Object-Oriented Programming (OOP) such as encapsulation, polymorphism, inheritance, and abstraction, there are several other important concepts and principles related to OOP: 

  

1. **Coupling:** 

   - **Definition:** Coupling measures the degree of dependence between classes or modules. It indicates how much one class knows about or relies on another. Low coupling is desirable as it leads to more maintainable and flexible systems. 

   - **Types:** 

     - **Low Coupling:** Classes have minimal knowledge of each other. Changes in one class have minimal impact on others. 

     - **High Coupling:** Classes are closely connected, and changes in one class may require changes in others. 

  

2. **Cohesion:** 

   - **Definition:** Cohesion measures the relatedness and interdependency of elements within a module (like a class or method). High cohesion is desirable as it leads to more maintainable and understandable code. 

   - **Types:** 

     - **High Cohesion:** Elements within a module are closely related and work together towards a common goal. 

     - **Low Cohesion:** Elements within a module have weak relationships and may not contribute to a common goal. 

  

3. **Association:** 

   - **Definition:** Association represents a bidirectional relationship between two classes. It can be a one-to-one, one-to-many, or many-to-many relationship. 

   - **Example:** In a university system, a `Student` class may be associated with a `Course` class through enrollment. 

  

4. **Aggregation:** 

   - **Definition:** Aggregation represents a "whole-part" relationship between classes. It implies that one class (the whole) contains another class (the part), but the part can exist independently. 

   - **Example:** In a car example, a `Car` class may have an aggregation relationship with a `Wheel` class. A `Car` has wheels, and wheels can exist independently. 

  

5. **Composition:** 

   - **Definition:** Composition is a stronger form of aggregation where the part cannot exist independently of the whole. If the whole is destroyed, all its parts are destroyed as well. 

   - **Example:** In a computer example, a `Computer` class may have a composition relationship with a `CPU` class. If the `Computer` is destroyed, the `CPU` is also destroyed. 

  

Understanding these additional concepts in OOP is crucial for designing systems with maintainability, flexibility, and clarity in mind. Properly managing coupling and cohesion helps create systems that are easier to modify and extend, while association, aggregation, and composition allow for more accurate modeling of real-world relationships in code. 

 



##Day 4 

###Introduction to Decision control 

 

Decision control in Java refers to the programming constructs that allow you to control the flow of execution based on certain conditions or decisions.  

 

There are mainly three decision-making structures in Java: 

  

1. if statement: 

   - The `if` statement evaluates a boolean expression and executes a block of code only if the condition is true. 

    

   Syntax: 

   ```java 

   if (condition) { 

       // Code to be executed if the condition is true 

   } 

   ``` 

  

2. **if-else statement:** 

   - The `if-else` statement allows the program to execute one block of code if the condition is true and another block if the condition is false. 

    

   Syntax: 

   ```java 

   if (condition) { 

       // Code to be executed if the condition is true 

   } else { 

       // Code to be executed if the condition is false 

   } 

   ``` 

  

3. **else-if ladder:** 

   - The `else-if` ladder allows checking multiple conditions one by one. If the condition is true, the corresponding block of code will be executed. If none of the conditions are true, the default else block (if present) will be executed. 

    

   Syntax: 

   ```java 

   if (condition1) { 

       // Code to be executed if condition1 is true 

   } else if (condition2) { 

       // Code to be executed if condition2 is true 

   } else if (condition3) { 

       // Code to be executed if condition3 is true 

   } else { 

       // Default code if no condition is true 

   } 

   ``` 

  

Example: 

  

```java 

int number = 10; 

  

// Example of if statement 

if (number > 0) { 

    System.out.println("Number is positive"); 

} 

  

// Example of if-else statement 

if (number > 0) { 

    System.out.println("Number is positive"); 

} else { 

    System.out.println("Number is not positive"); 

} 

  

// Example of else-if ladder 

if (number > 0) { 

    System.out.println("Number is positive"); 

} else if (number < 0) { 

    System.out.println("Number is negative"); 

} else { 

    System.out.println("Number is zero"); 

} 

``` 

  

These decision control structures help in writing programs that can make choices based on given conditions, allowing for dynamic behavior and more control over the flow of execution in Java programs. 

 

 

If Statement, IF ELSE statement, Nested If Statement 

 

 

 

`if` statement, `if-else` statement, and nested `if` statements in Java: 

  

### 1. If Statement: 

The `if` statement executes a block of code if the condition specified is true. 

  

Syntax: 

```java 

if (condition) { 

    // Code to execute if the condition is true 

} 

``` 

  

Example: 

```java 

int number = 10; 

  

// Example of if statement 

if (number > 0) { 

    System.out.println("Number is positive"); 

} 

``` 

  

### 2. If-Else Statement: 

The `if-else` statement executes one block of code if the condition is true and another block if the condition is false. 

  

Syntax: 

```java 

if (condition) { 

    // Code to execute if the condition is true 

} else { 

    // Code to execute if the condition is false 

} 

``` 

  

Example: 

```java 

int number = 10; 

  

// Example of if-else statement 

if (number > 0) { 

    System.out.println("Number is positive"); 

} else { 

    System.out.println("Number is not positive"); 

} 

``` 

  

### 3. Nested If Statement: 

Nested `if` statements contain an `if` statement within another `if` statement. This allows for more complex conditional logic. 

  

Syntax: 

```java 

if (condition1) { 

    // Code to execute if condition1 is true 

    if (condition2) { 

        // Code to execute if condition2 is true 

    } 

} 

``` 

  

Example: 

```java 

int x = 10; 

int y = 5; 

  

// Example of nested if statement 

if (x > 0) { 

    System.out.println("x is positive"); 

    if (y > 0) { 

        System.out.println("y is also positive"); 

    } 

} 

``` 

  

Nested `if` statements can have multiple levels, each level checking a specific condition.  

However, excessive nesting may lead to complex code and reduced readability, so it's essential to use them judiciously. 

 

Switch statement and the Tenary (?) operator 

 

 the `switch` statement and the ternary conditional operator (`? :`) in Java: 

  

### 1. Switch Statement: 

The `switch` statement is used to select one of many code blocks to be executed based on the value of a variable or expression. 

  

**Syntax:** 

```java 

switch (expression) { 

    case value1: 

        // Code to execute if expression equals value1 

        break; 

    case value2: 

        // Code to execute if expression equals value2 

        break; 

    // More cases... 

    default: 

        // Code to execute if expression doesn't match any case 

} 

``` 

  

**Example:** 

```java 

int day = 3; 

String dayName; 

  

// Example of switch statement to get the day name 

switch (day) { 

    case 1: 

        dayName = "Monday"; 

        break; 

    case 2: 

        dayName = "Tuesday"; 

        break; 

    case 3: 

        dayName = "Wednesday"; 

        break; 

    // More cases... 

    default: 

        dayName = "Invalid day"; 

} 

System.out.println("The day is: " + dayName); 

``` 

  

### 2. Ternary Operator (? :): 

The ternary operator `? :` is a concise way to express conditional statements. It evaluates a boolean expression and returns one of two values depending on the result of the evaluation. 

  

**Syntax:** 

```java 

result = (condition) ? valueIfTrue : valueIfFalse; 

``` 

  

**Example:** 

```java 

int x = 10; 

int y = 5; 

  

// Example of using the ternary operator 

String message = (x > y) ? "x is greater than y" : "y is greater than or equal to x"; 

System.out.println(message); 

``` 

  

The ternary operator evaluates the condition `(x > y)`. If the condition is true, it returns `"x is greater than y"`, otherwise, it returns `"y is greater than or equal to x"`. 

  

The `switch` statement allows for multiple conditional cases based on the value of an expression, while the ternary operator provides a concise way to create conditional expressions that return different values based on a condition.  

Both are useful tools for controlling the flow of execution in Java. 

 

##Day 5  

###Java Identifiers 

 

Identifiers are the names of variables, methods, classes, packages and interfaces. 

Unlike literals they are not the things themselves, just ways of referring to them. 

Identifiers must be composed of letters, numbers, the underscore _ and the dollar sign $. 

Identifiers may only begin with a letter, the underscore or a dollar sign. 

Java uses CamelCase as a practice for writing names of Identifiers (methods, variables, classes, packages and constants. 

 

Java Modifiers 

 

Modifiers are keywords that you add to those Identifiers to change their meanings. Java language has a wide variety of modifiers, including the following − 

Java Access Modifiers 

Non-Access Modifiers 

To use a modifier, you include its keyword in the definition of a class, method, or variable. The modifier precedes the rest of the statement, as in the following example, the words in bold blue are modifiers. 

 

Modifiers and non-access modifiers. 

In Java, access modifiers and non-access modifiers are used to control the visibility, accessibility, and behavior of classes, attributes, methods, and other elements within a program. 

  

Access Modifiers 

Access modifiers control the access levels of classes, methods, and variables in Java. There are four types of access modifiers: 

  

1. **Public (`public`):** 

   - The `public` access modifier makes the class, method, or variable accessible from anywhere in the Java environment. 

   - Public access is the highest level of accessibility. 

  

2. **Protected (`protected`):** 

   - The `protected` access modifier allows access within the same package and by subclasses (even if they are in a different package). 

   - Subclasses outside the package can access the protected members only through inheritance. 

  

3. **Default (Package-Private, no explicit modifier):** 

   - If no access modifier is specified, it is considered default. 

   - Default access allows access within the same package only. 

  

4. **Private (`private`):** 

   - The `private` access modifier restricts access to only within the same class. 

   - Private members are not accessible outside the class they are declared in. 

  

### Non-Access Modifiers for Classes: 

Non-access modifiers are used with classes to provide additional functionalities or control their behavior. 

  

1. **Final (`final`):** 

   - The `final` keyword prevents a class from being subclassed or modified. 

   - A `final` class cannot be extended. 

  

2. **Abstract (`abstract`):** 

   - The `abstract` keyword is used to create abstract classes, which cannot be instantiated on their own. 

   - Abstract classes may contain abstract methods (without a body) that must be implemented by their subclasses. 

  

### Non-Access Modifiers for Attributes and Methods: 

Non-access modifiers can also be applied to attributes (variables) and methods within a class. 

  

1. **Final (`final`):** 

   - Applied to attributes or variables, `final` makes them constants. Once initialized, their values cannot be changed. 

   - Applied to methods, `final` prevents the method from being overridden in subclasses. 

  

2. **Static (`static`):** 

   - `static` is used for class-level members (variables and methods). 

   - A static variable is shared among all instances of a class. It belongs to the class, not to instances. 

   - A static method belongs to the class rather than to any instance. It can be called without creating an instance of the class. 

  

3. **Transient (`transient`):** 

   - `transient` is used with variables to indicate that they should not be serialized when the object is serialized. 

   - The transient variable will not be persisted. 

  

4. **Volatile (`volatile`):** 

   - `volatile` keyword is used with variables to indicate that their value may be changed by multiple threads simultaneously. 

   - Ensures that the variable is always read from and written to main memory, not from a CPU cache. 

  

These modifiers provide additional control and functionality to classes, methods, and variables in Java, allowing developers to manage accessibility, inheritance, constants, and thread safety. 
