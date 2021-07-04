# dependency-injection-demo
In software engineering, dependency injection is a technique in which an object receives other objects that it depends on. It transfer the task of creating the object to someone else and directly using the dependency is called dependency injection


## Problems Solved
- How can an application or class be independent of how its objects are created?
- How can the way objects are created be specified in separate configuration files?
- How can an application support different configurations?

## Benefits of DI
- Dependency injection allows a client the flexibility of being configurable. Only the client's behavior is fixed. The client may act on anything that supports the intrinsic interface the client expects.
- Dependency injection can be used to externalize a system's configuration details into configuration files, allowing the system to be reconfigured without recompilation. Separate configurations can be written for different situations that require different implementations of components. This includes, but is not limited to, testing.
- Because dependency injection does not require any change in code behavior it can be applied to legacy code as a refactoring. The result is clients that are more independent and that are easier to unit test in isolation using stubs or mock objects that simulate other objects not under test. This ease of testing is often the first benefit noticed when using dependency injection.
- Dependency injection allows a client to remove all knowledge of a concrete implementation that it needs to use. This helps isolate the client from the impact of design changes and defects. It promotes reusability, testability and maintainability.
- Reduction of boilerplate code in the application objects, since all work to initialize or set up dependencies is handled by a provider component.
- Dependency injection allows concurrent or independent development. Two developers can independently develop classes that use each other, while only needing to know the interface the classes will communicate through. Plugins are often developed by third party shops that never even talk to the developers who created the product that uses the plugins.[24]
- Dependency Injection decreases coupling between a class and its dependency.
