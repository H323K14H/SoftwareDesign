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

## Strategy Pattern in Functional and Object-oriented Systems

A behavioural design pattern called the Strategy Pattern encapsulates a family of algorithms and defines them so they can be used interchangeably. Without changing its structure, it enables the client to select an algorithm at runtime from a family of algorithms.

The Strategy Pattern would be implemented in a functional system by designating procedures or functions as strategies. Depending on the chosen approach, the client code would call these functions, causing behaviour to change dynamically.

The Strategy Pattern is usually implemented with classes and interfaces in an object-oriented system. Every tactic is contained within a distinct class that carries out a shared interface. By switching objects that implement the same interface, the client code can transition between different strategies.

## Design Methodology for an Online Payment System

It is best to use an Agile Design Methodology, more specifically an Iterative and Incremental Development variation, when developing an online payment system that needs to function across multiple industries, such as ordering takeaway or buying clothes.

### Justifcation:
1) Adaptability: Agile approaches are renowned for their capacity to adjust to evolving needs. Being able to react swiftly to shifting demands is essential in a dynamic market where the payment system must serve multiple industries.

2) Constant Feedback: Agile development approaches encourage stakeholders to provide feedback on a regular basis. This means that the system can adapt to real user needs and experiences, guaranteeing optimal market fit.

3) Delivering a working product rapidly and adding features piecemeal makes it easier to enter new markets without requiring a comprehensive initial design. This technique is known as incremental delivery. The project can be divided into smaller increments or iterations.

4) Interdepartmental Teams: Agile places a strong emphasis on interdepartmental teams that can work together on different parts of the system, which is advantageous for a system that needs to service several industries.

5) Design with the user in mind: Agile strongly emphasises user-centered design and engagement. This method aids in the development of a user-friendly, industry-neutral payment system.

For a payment system that wants to capture as much of the market as possible across a variety of industries, the development team can maintain flexibility, responsiveness, and customer-focusedness by adhering to Agile principles.