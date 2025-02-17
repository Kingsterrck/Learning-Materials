# Paper2 Revision Note

## Class and Object
An ***object*** is an abstract entity and its components are data and actions.  

| Terms | Definitions |
| --- | --- |
| Constructor | A special kind of method, which is only declared once, that is called when an object is instantiated so that it initializes its data with specific values. Method name is same as the class name. |
| Accessor | A special kind of method that is called in order to read a specific data value of an object. Use the prefix “get” in the method name. |
>As the variables are declared as ***private*** in order protect data from accidental changes or from outside the object; 
>
>They cannot be accessed directly from outside this class;
>
>Therefore, ***public*** accessor methods are needed to ***permit access***; 

| Terms | Definitions |
| --- | --- |
| Mutator | special kind of method that is called in order to modify a private(hidden) variable in an object or class. Use the prefix “set” in the method name. |
| Signature | The methods name and all of its parameters and the types of these parameters. |
| Return value | Value that is passed back, returned, to the code that called the specific method.  |
| Identifier | The unique name of a program element |
| Object reference (pointer) | A reference is a variable whose value points to the location of an object (in memory) |
| Libraries | There consist of pre-written code, classes, procedures, methods etc. that programmers can use to add more functionality to their programs without having to rewrite the equivalent code.  |

>#### Advantages of using libraries: 
>
>Saves development time;  
>Since classes and their methods do not need to be rewritten;
>
>Promotes abstraction;  
>Because reusable code exists that functions without knowledge of internal working;
>
>Libraries contain error-free code;  
>Because it has been used and tested for many times;
>
>Promotes efficiency and organization;  
>As code will be shorter and easier to read;
>
>Familiarity with libraries;  
>Allow for easier maintenance or modification;

### Modifier
| Terms | Definitions |
|---|---|
| Public | Unlimited access. |
| Protected | Allows access to variable from within the package in which they are created. |
| Final | Prevents variables from being modified. |
| Static | Refers to variables that act on the class as a ***whole***. |

>#### Distinguish between a class and an instantiation.  
>
>A class is the blueprint of an object which does not occupy any memory in a program.
>
>An instantiation is the creation of an actual object which occupies enough memory to accommodate the object’s data and actions 

>#### M16 17, (c) discuss how the use of library classes simplifies the construction of the methods in parts(a) and (b) (asking for ArrayList)
>Can use the ArrayList library class; 
>
>Do not have to declare the size of the array; 
>
>Because the ArrayList automatically resizes itself; 
>
>Do not need to identify the index; 
>
>Because library class auto increments for you; 
>
>Could have used “sort list” instead of finding the correct place to insert object; 


---

## Object Oriented Programming (OOP)
### Definition
 A computer programming model that organizes software design around data, or ***objects***, rather than functions and logic. 

### Features
* Polymorphism  
* Encapsulation 
* Inheritance 

