## Adapter Design Pattern Example

This repository demonstrates the Adapter Design Pattern in Java. The Adapter Design Pattern allows incompatible interfaces to work together by providing a bridge between two classes. In this example, we adapt a Turkey interface to work with a Duck interface using an adapter class.

### Overview

The main class DuckTestDrive demonstrates the use of the adapter design pattern. The pattern is implemented by creating a TurkeyAdapter that allows a Turkey to be treated like a Duck.

### Classes

Duck: An interface with methods quack() and fly().
MallardDuck: A class implementing the Duck interface.
Turkey: An interface with methods gobble() and fly().
WildTurkey: A class implementing the Turkey interface.
TurkeyAdapter: A class implementing the Duck interface that adapts a Turkey to be used where a Duck is expected.

### Main Class: DuckTestDrive

The DuckTestDrive class contains the main method, which demonstrates the following:

1. Creating a MallardDuck object and using it directly.
2. Creating a WildTurkey object.
3. Wrapping the WildTurkey object in a TurkeyAdapter so that it can be treated as a Duck.
4. Testing the Duck interface using both the MallardDuck and the adapted Turkey.
