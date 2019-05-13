# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

    The biggest difference may be seen in the fact that while `forEach()` method simply calls a provided function on an array without returning anything (undefined), `map()` method actually returns a new array of same size by utilizing return values.

2. What is the difference between a function and a method?

    1. A function is a piece of code that is called by name while a method is called by name that is associated with an object.
    2. All data that is passed on a function is explicitly passed while a method is implicitly passed the object on which it was called.
    `In a nutshell, we may say that all methods are functions, but not all functions are methods.`

3. What is closure?

    A closure is a term in JavaScript used to define a function and all variable it has access to - scope chain. This extends to the fact that an inner function has access to variables within its own scope as well as the outer function's variables and not vice versa.

4. Describe the four rules of the 'this' keyword.

    `Rule 1: Window Binding`
    It states that if a function is contained in the global scope, the value of `this` inside of that function will be the window object.
    
    `Rule 2: Implicit Binding`
    It states that if a function is called by a preceding dot, the object before that dot is `this`.
    
    `Rule 3: New Binding`
    It states that if a constructor function is used, `this` refers to the specific instance of the object that is created and returned by the constructor function.
    
    `Rule 4: Explicit Binding`
    This states that if JavaScript’s call or apply method is used, `this` is explicitly defined.

5. Why do we need super() in an extended class?

    Super() is used to access and call functions on an object's parent. It can also be used directly on a constructor, where it appears alone and must be used before `this` keyword is used.
    It can be used in two ways:
    `super([arguments]);` which calls the parent constructor or
    `super.functionOnParent([arguments]);` which directly calls a function defined in the parent class

## Project Set up

Follow these steps to set up and work on your project:

- [X] Create a forked copy of this project.
- [X] Add PM as collaborator on Github.
- [X] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [X] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [X] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [X] You are now ready to build this project with your preferred IDE
- [X] Implement the project on your Branch, committing changes regularly.
- [X] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [X] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [X] Add your Project Manager as a Reviewer on the Pull-request
- [] PM then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [X] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [X] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [X] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [X] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
