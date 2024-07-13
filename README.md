# Object Oriented Programing
Object-oriented programming (OOP) is a computer programming model that organizes software design around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior.
OOP focuses on the objects that developers want to manipulate rather than the logic required to manipulate them. This approach to programming is well suited for software that is large, complex and actively updated or maintained. This includes programs for manufacturing and design, as well as mobile applications. For example, OOP can be used for manufacturing system simulation software.
The organization of an object-oriented program also makes the method beneficial for collaborative development, where projects are divided into groups. Additional benefits of OOP include code reusability, scalability and efficiency.

The first step in OOP is to collect all of the objects a programmer wants to manipulate and identify how they relate to each other -- an exercise known as data modeling.

Examples of an object can range from physical entities, such as a human being who is described by properties like name and age, to small computer programs, such as widgets.

Once an object is known, it is labeled with a class of objects that defines the kind of data it contains and any logic sequences that can manipulate it. Each distinct logic sequence is known as a method. Objects can communicate with well-defined interfaces called messages.

___

## History
OOP traces its roots back to the 1960s when computer scientists began to explore new ways of organizing and structuring code. The concept of objects, which encapsulate data and behavior, was introduced to improve software development processes.

One of the earliest programming languages that embraced OOP principles was Simula, developed in the 1960s by Ole-Johan Dahl and Kristen Nygaard. Simula introduced the concept of classes and objects, laying the foundation for modern OOP languages.
In the 1970s, Smalltalk was developed, which further popularized the use of OOP.

## The Rise of Object Oriented Programming
In the 1980s, OOP gained widespread popularity with the release of languages like C++ and Smalltalk. C++ combined the features of the C programming language with OOP concepts, making it a versatile and powerful language for software development. Smalltalk, on the other hand, was a pure object-oriented language that heavily influenced the design of subsequent OOP languages.
With the advent of Java in the mid-1990s, OOP became even more prevalent. Java’s platform independence and robustness made it a popular choice for developing enterprise-level applications. Today, OOP is a fundamental concept in many programming languages, including Python, Ruby, and C#.

Alternative methods to OOP include the following:
* Functional programming. This includes languages such as Erlang and Scala, which are used for telecommunications and fault-tolerant systems.
* Structured or modular programming. This includes languages such as PHP and C#.
* Imperative programming. This alternative to OOP focuses on function rather than models. Imperative programming languages include C++ and Java.
* Declarative programming. This programming method involves statements on what the task or desired outcome is but not how to achieve it. Declarative programming languages include Prolog and Lisp.
* Logical programming. This method, which is based mostly on formal logic and uses languages such as Prolog, contains a set of sentences that express facts or rules about a problem domain. It focuses on tasks that can benefit from rule-based logical queries.

## What are examples of object-oriented programming languages?
While Simula is credited as being the first object-oriented programming language, many other programming languages are used with OOP today. But some programming languages pair with OOP better than others. For example, programming languages that are considered pure OOP languages treat everything as objects. Other programming languages are designed primarily for OOP but with some procedural processes included. Some of the most popular programming languages are designed for, or with, OOP in mind.

For example, popular pure OOP languages include the following:
* Ruby
* Scala
* JADE
* Emerald

Programming languages designed primarily for OOP include the following:

* Java
* Python
* C++

Other programming languages that pair with OOP include the following:

* Visual Basic .NET
* PHP
* JavaScript

Most advanced programming languages enable developers to combine models because they can be used for different programming methods. For example, JavaScript and Scala can be used for OOP and functional programming.

___

## What is the structure of object-oriented programming?
The structure, or building blocks, of object-oriented programming include the following:

* __Classes__ are user-defined data types that act as the blueprint for individual objects, attributes and methods.
* __Objects__ are instances of a class created with specifically defined data. Objects can correspond to real-world objects or an abstract entity. When class is defined initially, the description is the only object that is defined.
* __Methods__ are functions that objects can perform. They are defined inside a class that describe the behaviors of an object. Each method contained in class definitions starts with a reference to an instance object. Additionally, the subroutines contained in an object are called instance methods. Programmers use methods for reusability or keeping functionality encapsulated inside one object at a time.
* __Attributes__ represent the state of an object. In other words, they are the characteristics that distinguish classes. Objects have data stored in the attributes field. Class attributes belong to the class itself and are defined in the class template.

## What are the main principles of OOP?

Object-oriented programming is based on the following principles:
* __Inheritance:__ Classes can reuse code and properties from other classes. Relationships and subclasses between objects can be assigned, enabling developers to reuse common logic, while still maintaining a unique hierarchy. Inheritance forces more thorough data analysis, reduces development time and ensures a higher level of accuracy. [learn more](./inharitace.md)
* __Encapsulation:__ The encapsulation principle states that all important information is contained inside an object and only select information is exposed. The implementation and state of each object are privately held inside a defined class. Other objects do not have access to this class or the authority to make changes. They are only able to call a list of public functions or methods. This characteristic of data hiding provides greater program security and avoids unintended data corruption.
* __Abstraction:__ Objects only reveal internal mechanisms that are relevant for the use of other objects, hiding any unnecessary implementation code. The derived class can have its functionality extended. This concept can help developers more easily make additional changes or additions over time.
* __Polymorphism:__ Objects are designed to share behaviors, and they can take on more than one form. The program determines which meaning or usage is necessary for each execution of that object from a parent class, reducing the need to duplicate code. A child class is then created, which extends the functionality of the parent class. Polymorphism enables different types of objects to pass through the same interface.
* __Coupling:__ This is the degree to which software elements are connected to one another. For example, if a class has its attributes change, then any other coupled class also changes.
•	Relationship. OOP relies on four fundamental relationships between classes: Inheritance, Association, Composition, and Aggregation. These relationships help us model complex systems and facilitate the creation of robust, maintainable, and scalable software. 
* __Dynamic Binding:__  In dynamic binding, the code to be executed in response to the function call is decided at runtime. Dynamic binding means that the code associated with a given procedure call is not known until the time of the call at run time. Dynamic Method Binding One of the main advantages of inheritance is that some derived class D has all the members of its base class B. Once D is not hiding any of the public members of B, then an object of D can represent B in any context where a B could be used. This feature is known as subtype polymorphism.
* __Message Passing:__ It is a form of communication used in object-oriented programming as well as parallel programming. Objects communicate with one another by sending and receiving information to each other. A message for an object is a request for execution of a procedure and therefore will invoke a function in the receiving object that generates the desired results. Message passing involves specifying the name of the object, the name of the function, and the information to be sent.

___

## What are the benefits of OOP?
Benefits of OOP include the following:

* __Modularity:__ Encapsulation enables objects to be self-contained, making troubleshooting and collaborative development easier.
* __Reusability:__ Code can be reused through inheritance, meaning a team does not have to write the same code multiple times.
* __Productivity:__ Programmers can construct new programs quickly through the use of multiple libraries and reusable code.
* __Easily upgradable and scalable:__ Programmers can implement system functionalities independently.
* __Interface descriptions:__ Descriptions of external systems are simple, due to message-passing techniques that are used for object communication.
* __Security:__ Using encapsulation and abstraction, complex code is hidden, software maintenance is easier and internet protocols are protected.
* __Flexibility:__ Polymorphism enables a single function to adapt to the class it is placed in. Different objects can also pass through the same interface.
* __Code maintenance:__ Parts of a system can be updated and maintained without needing to make significant adjustments.
* __Lower cost:__ Other benefits, such as its maintenance and reusability, reduce development costs.

## Cons
* __Performance:__ Pure OOP languages might have performance overhead due to heavy abstraction.
* __Learning Curve:__ Mastering OOP concepts can be challenging for beginners.
* __Flexibility:__ Strict adherence to OOP might limit certain programming possibilities.
