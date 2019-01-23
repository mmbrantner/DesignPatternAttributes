# DesignPatternAttributes

This library provides attributes corresponding to the most commonly used design patterns for object oriented programming.
Annotated classes, interfaces, functions or parameters will then automatically be verified.

What does that mean? At the start of the program a static constructor will be called. This method will find all the factories, adapters, bridges and so forth through reflection and check if they implement the pattern.
If a class is implement incorrectly (e.g. a singleton not providing access to it's instance), an exception will be thrown.

This creates the following advantages:  
- The developer has to implement the pattern correctly.
- Everyone else can see that a specific pattern was implement and implemented correctly.
- If they know the pattern, they have an easier time understanding the code.
- If they don't know the pattern, they can see how to use it and how to implement it correctly.
- The name of a class can be shortened, especially if the class implements multiple patterns. No more ```CustomerAccountAbstractFactoryManager```.

**Disclaimer:** This library is experimental, incomplete and up for debate. Most design patterns can be implemented at least 2 ways.

## Example

```csharp

```
