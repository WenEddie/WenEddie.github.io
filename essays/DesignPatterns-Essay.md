---
layout: essay
type: essay
title: The Wonders of Design Patterns
date: 2019-04-24
labels:
  - Software Engineering
  - Design Patterns
  - Meteor
---

## The Premise of Design Patterns
<img class="ui medium right rounded floated image" src="../images/DesignP.jpg">

In a world filled with recurring problems, how do we deal with them? When facing everyday problems, we often use the same type of approach towards a problem. Whether it is using a home remedy to deal with pain, or how to deal with frustration, everyone has their own methods to approach recurring problems. In terms of software engineering, programmers are often faced with similar types of situations or problems where using a certain approach would deem to be the best fit. This is a term called design pattern. A design pattern is a general and reusable approach, or template, applied to a common occurring problem. They are very essential in software engineering to the extent where programming languages have implemented design patterns to use without being explicitly known as design patterns.


## Encounters of Design Patterns
<img class="ui medium left rounded floated image" src="../images/DesignPattern.jpg">

Before I was exposed to the concept of design patterns, I have worked with classes in C++ and Java. This is a Prototype Design Pattern since classes uses the idea of creating objects. A more recent use of design patterns is called the Observer Design Pattern. It is an object that maintains its dependencies and when the object is changed, then the dependencies are notified by the changes made. An example of the Observer Design Pattern is reactive data in Meteor. A project that I contributed is called ManoaCart, which had MongoDB collections of user profiles, and products. Both of these collections are highly subjected to change, so the information that is changed are updated on MongoDB, which would be the reactive data in this case. Then, Meteor would receive the notification and will proceed to re-run Meteor on the updated information. This design pattern has been helpful when I needed to verify if data has been changed or not. Throughout my current experiences, design patterns are valuable tools used in software development.
