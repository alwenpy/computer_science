# Object Oriented Programming (OOP)

Object Oriented Programming is a fundamental programming paradigm which is based on the concepts of objects and data. 
It is the standard way of code that every programmer has to abide by for better readability and reusability of the code. 

### Objects
* An object can contain two types of data:
	1. Attributes.
	2. Procedures.

<br>

**Let us take an example:**

Consider a person to be an object.
* Their attributes are their height, weight, age, gender and many more details which gives us information about the person.
* The person can walk, run, jump, write, sing and perform many other actions and these are called procedures of the object Person.

### Classes
A class can be defined as the blue-print of an object. 
It does not store any data unlike the objects but it tells us what the object of that class does.

------------


## Concepts of OOP:
**There are four basic concepts of Object Oriented Programming:**

#### **1. Abstraction**
It refers to providing only necessary details for running a method to the user without providing any sensitive background information to the user.

For example, when you are driving a car, you only need to know how to drive it, use the accelerator and break. You do not care about the mechanism of how the car is running. This is how abstraction works.


#### **2. Encapsulation**
Encapsulation is a process of wrapping the data and the code, that operate on the data into a single entity.

It can be referred to as a protective wrapper that stops random access of code defined outside that wrapper so that the data is not mishandled and misused.

For example, if everyone is allowed to access the internal parts of the car, anyone who is inexperienced may mishandle the parts and cause an accident.


#### **3. Inheritance**
Inheritance is the ability to create a new class from an existing class.

Using inheritance, we can inherit a few or all members and functions from a Parent class to a Child class. The Child class may also have additional members and functions of its own.

For example, let us assume we have a class School which has attributes like Unique ID, Class Routine, etc and functions like Biometric Attendance System. 

There are two more classes called Student and Teacher. Now, both these classes can access the methods and function from the School class as well as have functions of their own like Assignment Submission or Assignment Grading respectively. 

#### **4. Polymorphism**
The word Polymorphism means having many forms. Using Polymorphism, a class can exhibit different functionalities even when they have a common interface.

Using Polymorphism, we can call the same member function but make it work differently depending on the type of object that calls the function. 

For example, let us consider a class called Addition. 

In case an object which has String data type members in it calls this class, the two strings are concatenated. But when the object has numeric data type members it it, the same class simply adds the two numbers.

Polymorphism eliminates the possibilities of rewriting almost the same code many times over differently for different objects.


#### **5. Overloading**

C++ has the ability to provide the operators with a special meaning for a data type, this ability is known as operator overloading. We can overload an operator ‘+’ in a class like String so that we can concatenate two strings by just using +.

In C++, we can overload:

1. Methods
2. Constructors
3. Indexed properties

#### **Types of overloading in C++**

Function overloading
Operator overloading

#### Implementing Operator Overloading in C++
Operator function must be either non-static (member function) or friend function to get overloaded. Operator overloading function can be applied on a member function if the left operand is an object of that class, but if the Left operand is different, then the Operator overloading function must be defined as a non-member function.
Operator overloading function can be made friend function if it requires access to the private and protected members of the class. For example, the operator op is an operator function where op is the operator being overloaded, and the operator is the keyword. Operator overloading can be achieved by implementing a function that can be either member function,non- member function or friend function.




**Hence, these four concepts of OOP helps in writing better modular and efficient codes.** 