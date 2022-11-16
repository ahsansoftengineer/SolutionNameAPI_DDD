# DOMAIN DRIVEN DESIGN ARCHETECTURE
> Using microservices means creating applications from loosely coupling services. The application consists of several small services, each representing a separate business goal. They can be developed and easily maintained individually, after what they are joint in a complex application.

## Microservices 
- Microservices is an architecture design model with a specific bounded context, configuration, and dependencies. These result from the architectural principles of the domain-driven design and DevOps. Domain-driven design is the idea of solving problems of the organization through code.

1. The team can also work on it independently
2. Provide Flexibility to work with several small teams
3. **Complexity Challenge** Complexity means interconnectedness, many different data sources, different business goals, etc.

## Repository
- The repository pattern is a collection of business entities that simplifies the data infrastructure. It releases the domain model from infrastructure concerns. The layering concept enforces the separation of concerns.



### Design patterns
- These programming paradigms are applied while developing software
- Design patterns are all about reusing code. 
- **Design Pattern:** Singleton Pattern, Factory Method Pattern, Abstract Factory Pattern, Builder Pattern, Prototype Pattern
- **Programming Paradigm** Procedural (POP), OOP, Funcational, 


### Programming Paradigm VS Archetecture VS Design Patter
#### Design Pattern:
- A design pattern is a useful abstraction that can be implemented in any language. It is a "pattern" for doing things. Like if you have a bunch of steps you want to implement, you might use the 'composite' and 'command' patterns so make your implementation more generic. Think of a pattern as an established template for solving a common coding task in a generic way.

#### Programming Paradigm:
- Something like "Functional Programming", "Procedural Programming", and "Object Oriented Programming". The programming paradigm and the languages that use them inform how the code gets written. For example, in Object Oriented programming the code is divided up into classes (sometimes a language feature, sometimes not (e.g. javascript)), and typically supports inheritance and some type of polymorphism. 

#### Application Architecture: 
- Application architecture involves choosing the platform, languages, frameworks used. This is different than software architecture, which speaks more to how to actually implement the program given the software stack.

### POP VS OOP
- The key difference between OOP and POP is that an OOP divides a program into smaller objects, whereas POP divides a program into smaller procedures or functions to arrive at the results of the problem

#### POP
Procedural Oriented Programming is one of the programming methods where the main focus is on functions or procedures required for computation, instead of data.
#### OOP
1. Abstraction: Abstract classes and interfaces are used to hide the internal details and show the functionality.
- The user will get to understand of “what” than “how”.

2. Inheritance: An object using the methods and properties of an existing object, is called inheritance. It enhances code reusability. 
- Multi-level
- Single
- Hybrid 
- Multiple
- Hierarchical

3. Encapsulation: Data is secured with encapsulation, and binds the attributes and methods together. It restricts access to some parts of the code, if they are not needed.
4. Polymorphism: With polymorphism, an object can function in multiple ways. Examples: Method overloading and method overriding.