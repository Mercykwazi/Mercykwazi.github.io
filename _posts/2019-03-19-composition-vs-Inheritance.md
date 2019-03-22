---
Layout:
Title: "Composition vs Inheritance"
date: 2019-03-19 09:40
categories:
---

# Inheritance
Inheritance in Java is a mechanism in which one object acquires all the properties and behaviors of a parent object.
The idea behind inheritance in Java is that you can create new classes that are built upon existing classes.
When you inherit from an existing class, you can reuse methods and fields of the parent class.you can also add your own methods in that class if you want to.
It represents a IS-A relationship which is also known as a parent-child relationship.

Syntax
class Newclass extends Superclass{  
   //methods and fields  
}  
The extends keyword indicates that you are making a new class that derives from an existing class.

# Composition
Composition in java is the design technique to implement has-a relationship in classes.
We can use java inheritance or Object composition in java for code reuse.
The benefit of using composition in java is that we can control the visibility of other object to client classes and reuse only what we need.


