# Zen

<p align="center">
  <img width="350" src="./enso.png">
</p>

## Principles of Design

> “It is not enough for code to work.”
>
> ― Robert C. Martin

1. DRY – Don’t Repeat Yourself
1. KISS – Keep It Simple Stupid
1. YAGNI – You Aren’t Gonna Need It
1. SOLID:  
    * S – Single Responsibility Principle
    * O – Open-Closed Principle
    * L – Liskov Substitution Principle
    * I – Interface Segregation Principle
    * D – Dependency Inversion Principle

[SOLID in wikipedia](https://en.wikipedia.org/wiki/SOLID)

[Summary of 'Clean code' by Robert C. Martin](https://gist.github.com/wojteklu/73c6914cc446146b8b533c0988cf8d29)

## Code Review

> A key point here is that there is no such thing as “perfect” code—there is only better code.
> Instead of seeking perfection, what a reviewer should seek is continuous improvement

In general, reviewers should favor approving a changelist once it is in a state where 
it definitely improves the overall code health of the system being worked on, 
even if the changelist isn’t perfect.

That is the senior principle among all of the code review guidelines.

### Principals

* Technical facts and data overrule opinions and personal preferences.

* On matters of style, the style guide is the absolute authority. 

* Aspects of software design are almost never a pure style issue or just 
a personal preference. They are based on underlying principles and should be 
weighed on those principles, not simply by personal opinion. 
Sometimes there are a few valid options. If the author can demonstrate 
(either through data or based on solid engineering principles) that several 
approaches are equally valid, then the reviewer should accept the preference of
the author. Otherwise the choice is dictated by standard principles of software 
design.

* If no other rule applies, then the reviewer may ask the author to be 
consistent with what is in the current codebase, as long as that doesn’t worsen 
the overall code health of the system.


### Code reviews should look at

* Design
    
    *Is the code well-designed and appropriate for your system?*

* Functionality
    
    *Does the code behave as the author likely intended? Is the way the code 
    behaves good for its users?*

* Complexity
    
    *Could the code be made simpler? Would another developer be able to easily 
    understand and use this code when they come across it in the future?*

* Tests
    
    *Does the code have correct and well-designed automated tests?*

* Naming

    *Did the developer choose clear names for variables, classes, methods, etc.?*

* Comments

    *Are the comments clear and useful?*

* Style: 
    
    *Does the code follow our style guides?*

* Documentation

    *Did the developer also update relevant documentation?*

[Google Engineering Practices Documentation](https://google.github.io/eng-practices)
