# dependency-injection-demo
In software engineering, dependency injection is a technique in which an object receives other objects that it depends on. It transfer the task of creating the object to someone else. is a design pattern in which a class requests dependencies from external sources rather than creating them.


## Problems Solved
- How can an application or class be independent of how its objects are created?
- How can the way objects are created be specified in separate configuration files?
- How can an application support different configurations?

## Benefits of DI
- Make testing easier
- Boilerplate code is reduced, as initializing of dependencies is done by the injector component.
- Dependency injection can be used to externalize a system's configuration details into configuration files, allowing the system to be reconfigured without recompilation. Separate configurations can be written for different situations that require different implementations of components. This includes, but is not limited to, testing.
