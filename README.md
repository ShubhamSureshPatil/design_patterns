# Design Patterns
Design Patterns for Software Design

In software engineering, a software design pattern is a general, reusable solution to a commonly occurring problem within a given context in software design. 

## Structural Patterns

In software engineering, creational design patterns are design patterns that deal with object creation mechanisms, trying to create objects in a manner suitable to the situation. The basic form of object creation could result in design problems or in added complexity to the design. Creational design patterns solve this problem by somehow controlling this object creation.

Creational design patterns are composed of two dominant ideas. One is encapsulating knowledge about which concrete classes the system uses. Another is hiding how instances of these concrete classes are created and combined

    1. Builder Design Pattern: how a composite object gets created

    Create an Object by composing other complex objects <b> step by step </b>. The step by step creation is handled by a <b>Director</b>

    2. Singleton Design Pattern: the sole instance of a class
    Define a class that has only one instance and provide a global point of access to that instance 

            1. Requirements
                1. One and only one instance 
                2. Global Access
                3. No Ownership
                4. Lazy Initialization

            2. Advantages:
                1. Save memory
                2. Single access point - logger, database connections
                3. Flexibility 

            3. Usage:
                1. Threadpools
                2. logging and caching
                3. Configuration Settings (game setting, application settings)
                
            4. To create
                1. Static Member
                2. Private Constructor
                3. Static Function
