## Objectives
My objective for this talk is to give new Pythonistas an overview of how memory management works in Python. I'd like to scratch the surface of the topics of references, scope, and garbage collection to give them a comprehensive overview. 

## Description
As a new python developer, do you find memory management in Python confusing? Come to this talk to learn about the basics of how Memory Management works in Python. We'll cover the concepts of reference counting, garbage collection, weak references, __slots__, and the Global Interpreter Lock. 

## Abstract
As a new Python developer, trying to understand how memory management works in python can feel like a daunting task.

The documentation immediately jumps into difficult to follow concepts, especially if you don't have a background in Computer Science.

I'd like to provide a simple, easy to follow overview of the concepts that a developer needs to be familiar with in order to scratch the surface of how memory management and garbage collection works in Python. 

### Outline
## INTRODUCTION (5 MINS)
- How Python objects are stored in memory
- Introduction to the concept of Reference Counting
- Reviewing scope and the del statement
- Differences between mutable and immutable types
- Tools to help us examine our environment - the id() function

## WEAKREF (5 MINS)
- Basics of weakref
- How and where is weakref used internally
- When you might want to use weakref in your own projects using caches as an example

## GARBAGE COLLECTION (5 MINS)
- How often is garbage collection run in Python?
- Which Garbage Collection strategy does Python employ?
- Advantages and drawbacks of reference count garbage collection vs. traced garbage collection.
- What happens when you have cyclical objects?

## __SLOTS__ (5 MINS)
- What happens when you define __slots__ in a class definition.
- Under what circumstances would we want to do this.
- With great power comes great responsibility. What can happen if we abuse __slots__.

## THE GIL (5 MINS)
- What is the Global Interpreter Lock
- What role does the Global Interpreter Lock play in memory management for multi-threaded Python applications
- What are the advantages and disadvantages of this approach - What trade offs were made?

## Q&A (5 MINS) 
