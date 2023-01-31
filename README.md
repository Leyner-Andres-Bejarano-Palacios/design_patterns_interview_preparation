# design_patterns_interview_preparation
By now you already know what "interview preparation" repos are about, so enjoy.

## Theorical Questions Section

### Theorical Question 1

Do you know what the MVC model is ?

<details><summary><b>Answer</b></summary>

MVC consists of three kinds of objects. The Model is the application object, the View is
its screen presentation, and the Controller defines the way the user interface reacts to
user input. Before MVC, user interface designs tended to lump these objects together.
MVC decouples them to increase flexibility and reuse.

MVC decouples views and models by establishing a subscribe/notify protocol between
them. A view must ensure that its appearance reflects the state of the model. Whenever
the model's data changes, the model notifies views that depend on it. In response, each
view gets an opportunity to update itself. This approach lets you attach multiple views
to a model to provide different presentations. You can also create new views for a model
without rewriting it.

</details>

<details><summary><b>Source</b></summary>
Design Patterns: Elements of Reusable Object-Oriented Software - pag 4
</details>

### Theorical Question 2

What desing patterrns do you know ?

<details><summary><b>Answer</b></summary>

Abstract Factory (87) Provide an interface for creating families of related or dependent
objects without specifying their concrete classes.

Adapter (139) Convert the interface of a class into another interface clients expect.
Adapter lets classes work together that couldn't otherwise because of incompat-
ible interfaces.

Bridge (151) Decouple an abstraction from its implementation so that the two can vary
independently.

Builder (97) Separate the construction of a complex object from its representation so
that the same construction process can create different representations.

Chain of Responsibility (223) Avoid coupling the sender of a request to its receiver by
giving more than one object a chance to handle the request. Chain the receiving
objects and pass the request along the chain until an object handles it.

Command (233) Encapsulate a request as an object, thereby letting you parameter-
ize clients with different requests, queue or log requests, and support undoable
operations.

Composite (163) Compose objects into tree structures to represent part-whole hierar-
chies. Composite lets clients treat individual objects and compositions of objects
uniformly.

Decorator (175) Attach additional responsibilities to an object dynamically. Decorators
provide a flexible alternative to subclassing for extending functionality.

Facade (185) Provide a unified interface to a set of interfaces in a subsystem. Facade
defines a higher-level interface that makes the subsystem easier to use.

Factory Method (107) Define an interface for creating an object, but let subclasses de-
cide which class to instantiate. Factory Method lets a class defer instantiation to
subclasses.

Flyweight (195) Use sharing to support large numbers of fine-grained objects effi-
ciently.

Interpreter (243) Given a language, define a represention for its grammar along with
an interpreter that uses the representation to interpret sentences in the language.

Iterator (257) Provide a way to access the elements of an aggregate object sequentially
without exposing its underlying representation.

Mediator (273) Define an object that encapsulates how a set of objects interact. Me-
diator promotes loose coupling by keeping objects from referring to each other
explicitly, and it lets you vary their interaction independently.

Memento (283) Without violating encapsulation, capture and externalize an object's
internal state so that the object can be restored to this state later.

Observer (293) Define a one-to-many dependency between objects so that when one
object changes state, all its dependents are notified and updated automatically.

Prototype (117) Specify the kinds of objects to create using a prototypical instance, and
create new objects by copying this prototype.

Proxy (207) Provide a surrogate or placeholder for another object to control access to
it.

Singleton (127) Ensure a class only has one instance, and provide a global point of
access to it.

State (305) Allow an object to alter its behavior when its internal state changes. The
object will appear to change its class.

Strategy (315) Define a family of algorithms, encapsulate each one, and make them
interchangeable. Strategy lets the algorithm vary independently from clients that
use it.

Template Method (325) Define the skeleton of an algorithm in an operation, deferring
some steps to subclasses. Template Method lets subclasses redefine certain steps
of an algorithm without changing the algorithm's structure.

Visitor (331) Represent an operation to be performed on the elements of an object
structure. Visitor lets you define a new operation without changing the classes of
the elements on which it operates.

</details>

<details><summary><b>Source</b></summary>
Design Patterns: Elements of Reusable Object-Oriented Software - pag 8
</details>