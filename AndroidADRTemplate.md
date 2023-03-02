# Android Application ADR for module

# Title(ADR-AN-0000)[REQUIRED]
Project, Module(Catalog), Class, which are touched by decision. 
Sample: Sample project. User profile.

## Status[REQUIRED]
- [ ] PROPOSED
- [ ] ACCEPTED
- [ ] REJECTED
- [ ] DEPRECATED
- [ ] SUPERSEDED

## SSR or COMPOSE[OPTIONAL]
### Will be this module used on both platforms(ios and android)?
- [ ] Yes
- [ ] No 
### Should the module participate in A/B testing and experiments?
- [ ] Yes
- [ ] No 
### Should the module be updated by hot reload?
- [ ] Yes
- [ ] No
### 2 of 3 means that SSR must be used for screen

## MVI or MVVM(UI modules only)[OPTIONAL]
### Descibe of intents for this screen/module
- [x] Loading
- [x] Content
- [x] Error
- [ ] Intent1
- [ ] Intent2
### If more than 5 intents MVI recommended

## List of used patterns, that can be used in the module[OPTIONAL]
### Creational Design Patterns
- [ ] Abstract Factory. Allows the creation of objects without specifying their concrete type. 
- [ ] Builder. Uses to create complex objects.
- [ ] Factory Method. Creates objects without specifying the exact class to create.
- [ ] Prototype. Creates a new object from an existing object.
- [ ] Singleton. Ensures only one instance of an object is created.
### Structural Design Patterns
- [ ] Adapter. Allows for two incompatible classes to work together by wrapping an interface around one of the existing classes.
- [ ] Bridge. Decouples an abstraction so two classes can vary independently.
- [ ] Composite. Takes a group of objects into a single object.
- [ ] Decorator. Allows for an object’s behavior to be extended dynamically at run time.
- [ ] Facade. Provides a simple interface to a more complex underlying object.
- [ ] Flyweight. Reduces the cost of complex object models.
- [ ] Proxy. Provides a placeholder interface to an underlying object to control access, reduce cost, or reduce complexity.
### Behavior Design Patterns
- [ ] Chain of Responsibility. Delegates commands to a chain of processing objects.
- [ ] Command. Creates objects which encapsulate actions and parameters.
- [ ] Interpreter. Implements a specialized language.
- [ ] Iterator. Accesses the elements of an object sequentially without exposing its underlying representation.
- [ ] Mediator. Allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
- [ ] Memento. Provides the ability to restore an object to its previous state.
- [ ] Observer. Is a publish/subscribe pattern which allows a number of observer objects to see an event.
- [ ] State. Allows an object to alter its behavior when its internal state changes.
- [ ] Strategy. Allows one of a family of algorithms to be selected on-the-fly at run-time.
- [ ] Template Method. Defines the skeleton of an algorithm as an abstract class, allowing its sub-classes to provide concrete behavior.
- [ ] Visitor. Separates an algorithm from an object structure by moving the hierarchy of methods into one object.

## Sources of data[OPTIONAL]
### API requests
* /path/path 
* /path/path
### Database entities/tables
* EntityOne
* EntityTwo

## Firebase services[OPTIONAL]
### List of firebase services that can be used
- [ ] Firestore
- [ ] RemoteConfig
- [ ] Firebase auth
- [ ] Cloud Messaging
- [ ] Another one ...

## What classes are covered by tests or should be covered[REQUIRED]
- [x] UseCaseOne
- [ ] UseCaseTwo

## Plant uml diagram[REQUIRED]
[UML Diagram](plant_uml_sample.puml)