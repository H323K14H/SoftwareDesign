# Software Design Methodologies:

## Cohesion and Coupling in Structured design:

| Cohesion | Coupling |
| ----- | ----- |
| Cohesion is the concept of intra-module | Coupling is the concept of inter-module. |
|Cohesion represents the relationship within a module. | Coupling represents the relationships between modules. |
| Increasing cohesion is good for software. | Increasing coupling is avoided for software. |
| Cohesion represents the functional strength of modules. | Coupling represents the independence among modules. |
| Highly cohesive gives the best software. | Whereas loosely coupling gives the best software. |
| In cohesion, the module focuses on a single thing. | In coupling, modules are connected to the other modules. |
| Cohesion is created between the same module. | Coupling is created between  two different modules. |

### There are 6 Types of cohesion:
1) Functional Cohesion.
2) Procedural Cohesion. 
3) Temporal Cohesion.
4) Sequential Cohesion.
5) Layer Cohesion.
6) Communication Cohesion.

### There are 6 Types of coupling:
1) Common Coupling.
2) External Coupling. 
3) Control Coupling.
4) Stamp Coupling.
5) Data Coupling
6) Content Coupling.



## Top-down and Bottom-up design:

A method known as "top-down design" breaks down a system into smaller, more manageable parts by starting with the highest-level modules or components. It is a top-down method that commences with the general structure of a system and progressively disassembles it into smaller parts.

The opposite strategy is called "Bottom-Up Design," which begins with the smallest, most fundamental parts and works its way up to larger, more intricate modules. It's a bottom-up method that starts with separate components and works its way up to a finished system.

As it concentrates on defining and organising functions or procedures before combining them to create a system, function-oriented design frequently corresponds more with the Bottom-Up approach. However, the particular project needs will determine whether to use a top-down or bottom-up design approach.

## Class Diagrams:

The best use cases for a class diagram are within the framework of object-oriented design techniques. It is a diagram that shows how classes relate to one another in an object-oriented system. Class diagrams are crucial for modelling object-oriented systems, such as software programmes and databases, as they give a visual depiction of the system's structure.

## Four Pillars of Object-oriented Programming:

Encapsulation is the idea of combining data and the methods that manipulate it into a single unit, called a class. Data protection and a clear interface for interacting with the object are provided, and access to certain components of the object is restricted while others are left exposed.

A new class (the subclass or derived class) can inherit traits and behaviours from an existing class (the superclass or base class) thanks to inheritance. It creates a "is-a" relationship between classes and encourages code reuse.

The ability to treat objects of different classes as belonging to a common superclass is known as polymorphism. It supports method overriding, which improves flexibility and extensibility by allowing various classes to provide their own method implementations.

Abstraction: By focusing on the important aspects of a class and disregarding the rest, abstraction is the process of simplifying a complex reality. It offers a high-level, clear picture of the characteristics and behaviour of an object.
