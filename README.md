# Encapsulation



Encapsulation is one of the OOPS concepts in Java. It is wrapping the code or methods(properties) and the fields or variables together as a single unit. In object-oriented programming, we can call a class, interface, etc. as a single unit as an example. We can visualize it like a medicine capsule inside which there are multiple components existing like fields and methods of a java class.

Mobile is a good example of encapsulation. It has many apps and features inside it. And overall it is a phone.

It is a grouping mechanism that hides the data of a class. So, other classes can not access it. It is a protected shield that prevents the data from being accessed by the code outside the shield.  To encapsulate the data, we declare the variables as a private variable inside the class. Those private variables can only be accessed only with in the class. To allow the other classes to access the private variables, we need to modify into” public getter and setter methods“. Encapsulation is also known as data hiding or tightly encapsulation.



### Setter methods are always void.
### Getter methods are always return type.

 We can not directly read and set the values of private variables/fields, Java will provide us with getter and setter methods for their accessibility outside the class.

## There are two ways to initialize the data in java.
### 1. Constructors
### 2. Setter methods 

“Initialization is when we put a value in a variable, this happens while we declare a variable. “

Example: 
int x = 7; 
String myName = "Emi"; 
Boolean myCondition = false;

Note: “You can encapsulate fields and methods inside a single class”.

## Features

1. This is important for hiding the data for security reasons.
2. It is easier to maintain the code without affecting other parts of the code.
3. Encapsulation makes sure that sensitive data is hidden from the user.
4. A class can control its own data.
5. if a data is declared “private”, then it can only be accessed within the same class. No outside class can access data (variable).
6. if you need to access these variables, you have to use public “getter” and “setter” methods.
7. For decoupling component: These decoupled components (bundle) can be developed, tested, and debugged independently.


## Key Points to Remember about encapsulation in Java

There are two golden rules to remember about encapsulation in Java:

1. Declare all the variables as private
2. Write public getter and setter methods to access these variables

Also, data hiding and data encapsulation are interchangeably used in most cases but are different.


## What is the difference between abstraction and encapsulation?

Abstraction is hiding implementation.

 Encapsulation is hiding the data in a single entity or unit and protecting information from the outside.


______________________

Data hiding is when data is always private. Encapsulation has data that can be public or private data.







# Inside getter and setter methods,  We write logics also.  For example:

class Person {

  private int age;


  public void setAge(int age) {

    if (age >= 0) {

      this.age = age;

    }

  }

}




