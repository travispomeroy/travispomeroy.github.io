---
title: "Do Design Patterns Increase Code Complexity"
categories:
  - Design Patterns
tags:
  - Design Patterns
---

### Background:
I help organize a small tech club for my office.  Its nothing special, just a group of 
developers that read technology books.  We meet-up once a week to discuss what we have read 
and keep moving on.  The makeup of the group is mostly junior engineers.  Right now, we are 
reading Head First Design Patterns as suggested by one of the junior developers.  While doing 
research on this book I found some blogs that were, let's say, anti design patterns.  This 
post focuses on the anti design pattern argument.

Let me come clean, and just get it out of the way, I love Object Oriented Design.  I love 
the way object oriented code feels.  I love the way it reads.  I love the way I can test it.
  For me, there is just a sense of naturalness to well written object oriented code.  So 
  while doing research on the Head First Design Patterns book, I found an opinion that 
  suggested this book should not be read by junior developers.  Which is a really fun 
  argument to think about.  And basically the argument is that design patterns are too 
  complex to be teaching a junior developer, and that design patterns increase code 
  complexity, so why would you want to teach a junior developer how to increase code 
  complexity?  Let's take each point one at a time.
  
### Should Junior Developers Learn Design Patterns
Absolutely! I understand that there are some really complicated design patterns out there, 
and I understand that there are also really poor uses of design patterns out there, but why 
on Earth would you want to limit your ability to communicate with your Junior developers?  
What I mean by that, for me, one of the strongest positives of design patterns is that it 
enables us to easily communicate with one another.  If I say, "maybe we should use a factory
 to handle the creation of all these objects," then I would expect my fellow engineers to 
 know what I'm talking about.  And some of these patterns are so ubiquitous in third party 
 libraries and frameworks, that I would highly recommend my junior developers to learn them.  
 
### Do Design Patterns Increase Code Complexity
What code written into an application does not increase the complexity of the application?  
As soon as we write code, we are increasing the complexity of the application design pattern
 or not.  For me, engineering is all about tradeoffs.  If you can justify the trade-off for
  not implementing a pattern to solve your problem, then that's awesome!  I do not think 
  design patterns inherently increase code complexity.  They do tend to increase the surface
   area of your solution, but is that such a bad thing?  Would you rather have one 1200 line
    class that gets used in 75% percent of your application, or would you rather have 
    multiple smaller classes?  That's a tradeoff you have to make for your team and your 
    application.  

### Final Thoughts
I will use design patterns to the best of my team's ability.  If I use a pattern that my 
team is unfamiliar with, then we can have a knowledge transfer session, and reevaluate 
whether or not the pattern meets our needs.  I will also go out of my way to help junior 
developers learn more about design patterns.  I honestly believe it will help them read code
 faster, help them codify solutions faster to reoccurring problems, and definitely help them 
 communicate with other software engineers.
