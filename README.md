# OOP principles

- **DRY (don't repeat yourself)** - don't write duplicate code, instead use Abstraction. Create method or public final constant -> Benefit: better maintenance
- **KISS** - Keep it simple, stupid
- **TDD** - Test-driven development
- **Encapsulate** - Encapsulate (use private) everything that could be change -> Benefit: easy to test and maintain. i.e. Factory design pattern
- **Favour Composition over Inheritance** - Composition allows to change the behaviour of a class at run-time by setting property during runtime. Better reusability of code
- **Programming for Interface, not implementation** - It will lead to flexible code which can work with any new implementation of an interface. So use interface type on variables, return types of method or argument type of methods in Java.
- **Delegation principle** - Don't do all stuff by yourself, delegate it to respective class. The benefit of this design principle is no duplication of code and pretty easy to modify behaviour. i.e. equal and Compare in Java

### SOLID
- **Single Responsibility Principles (SRP)** - One class should have one and only one responsibility
- **Open Close Principle (OCP)** - Software components should be open for extension (new functionality) but closed for modification 
- **Liskov’s Substitution Principle (LSP)** - Derived types must be completely substitutable for their base types. It means that derived class or subclass must enhance functionality, but not reduce them.
- **Interface Segregation Principle (ISP)** - Clients should not be forced to implement unnecessary methods which they will not use. (This happens mostly when one interface contains more than one functionality, and the client only needs one functionality and no other.)
- **Dependency Inversion Principle (DIP)** - Depend on abstractions, not on concretions. Any object which is injected is easy to test with a mock
