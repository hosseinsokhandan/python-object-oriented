- [Introduction to OOP](#introduction-to-oop)
  * [Object-oriented Stages](#object-oriented-stages)
    + [What is object-oriented analysis?](#what-is-object-oriented-analysis-)
    + [What is object-oriented design?](#what-is-object-oriented-design-)
    + [What is object-oriented programming?](#what-is-object-oriented-programming-)
  * [Data And Objects](#data-and-objects)
    + [How data is related to an object?](#how-data-is-related-to-an-object-)
    + [Attributes](#attributes)
  * [Hiding Details, Interface](#hiding-details--interface)
  * [Information Hiding and Encapsulation are not same](#information-hiding-and-encapsulation-are-not-same)
  * [Abstraction](#abstraction)
  * [Composition](#composition)
  * [Inheritance](#inheritance)
  * [Polymorphism](#polymorphism)
    + [Duck Typing](#duck-typing)
  * [Lesson Learnt](#lesson-learnt)
  * [Vocabulary](#vocabulary)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Introduction to OOP

## Object-oriented Stages
Let's start by defining Object (in software) and Orientation.

**Object**: A collection of *data* and associated *behaviors*.
**Orientation**: Directed toward something.
**Object-oriented**: Functioning directly toward modeling objects.
**Class**: Classes describes objects.

Object-Oriented Consist of 3 major stages:
1. Object-oriented analysis (OOA).
2. Object-oriented design (OOD).
3. Object-oriented programming (OOP).

### What is object-oriented analysis?
The process of **Identifying the objects and interactions between those objects**. OOA is about *What* needs to be done. The output of the analysis stage is a *set of requirements*. In addition, Dusty Philips claims that analysis is a misnomer, a better turn of phrase might be **object-oriented exploration** as process is likely an explorations rather analysis. Personally, I couldn't agree more.

initial stages are:
* Interviewing customers
* Studying their processes
* Eliminating possibilities

> Eliminating Possibilities is a problem-solving strategy through which possible answers are removed until only the correct answer remains.

<br />


### What is object-oriented design?
The process of **converting  the former set of requirements into an implementation specification**. OOD is about *How* things should be done. The output of the design stage is a *implementation specification*.


### What is object-oriented programming?
The process of **converting this perfectly-defined design into a working program** that **does exactly what the CEO wanted**.


take a glimpse at the below table

| Stage | Definition | Output | what is it about? |
| ------------ | ------------ | ------------ | ------------ |
| OOA | Identifying the objects and interactions between them. | set of requirements | What |
| OOD | conver the former set of requirements into an implementation specification | implementation specification | How |
| OOP | converting this perfectly-defined design into a working program | software | horray! | 


## Data And Objects

### How data is related to an object?
> Data represents the individual characteristics of a certain object.

What does it mean?

In order to grasp a better picture of what is the responsibility of data in objects, imagine a class responsible for creating human objects. Also consider this object having some human-like properties such as kindness. By changing the value of kindness from 0 to 100 your human object will be a kindest human (object) you'll ever seen. In contrast, if you let it be 0 this human (object) is an unkind one. So, you may have a better understanding of how data represent the characteristics of a certain object.

### Attributes
> Attributes are frequently reffered to as members or properties. Some authors argue that attributes and properties have different meaning, usually that attributes are settable while properties are read-only. In Python, the concept of read-only is rather pointless, so these words can be used interchangebly.


## Hiding Details, Interface
The key concept of modeling an object is to determine what is the object's publis interface. The interface is what you let other objects access from the object. It is important as it defines how this object can be treated.

## Information Hiding and Encapsulation are not same
Encapsulated data is not necessareily hidden. If you put something in a capsule, is it hidden from you? How about digging the ground and burry it under one metter dust? this is the diff between Encapsulation and Information Hiding. In Python wo don't have really information hiding.


## Abstraction
> Abstraction means dealing with the level of detail that is most appropriate.

Also
> It is the process of hiding information with seperate public and private interfaces.



## Composition
> It is the act of collecting several objects together to create new one.


## Inheritance
The *is a* relationship is formed by inheritance. The child class will inherit properties and methods from the parent class. In addition, it can have its own properties and methods.


## Polymorphism
> Polymorphism is the ability to treat a class differently, depending on which subclass is implemented.

### Duck Typing
> This sort of polymorphism in Python is typically referred to as duck typing: if it walks like a
duck or swims like a duck, it's a duck. We don't care if it really is a duck (is a being a
cornerstone of inheritance), only that it swims or walks.

## Lesson Learnt
1. Tthe most important part of object modeling, is providing interfaces.

2. > Objects represent nouns, methods are normally verbs, and attributes may show up as adjectives.
3. *If it walks like a duck or swims like a duck, it's duck.*
4. **Owning a hammer does not turn screws into nails.**

5. > objects are tools, not rules.

## Vocabulary
Here are list of new words that I learned during chapter 1.
1. tangble
2. misnomer
3. turn of phrase
4. murkier
5. barrels
6. disparaged
7. orchard
8. postulated
9. waned 
10. parlance
11. cornerstone
12. remiss
13. inclination
14. whirlwind
15. taxonomy
