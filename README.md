# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your team lead

1. Describe the biggest difference between `.forEach` & `.map`.

forEach() = executes the provided function once for each array element / does not actualy return anything as it simply calls the provided function
map() = creates a whole new array with the results of calling a provided function on every element in the calling array / utilizes return values and returns a new Array of the same size


2. What is the difference between a function and a method?
method = a function that belongs to an object

A function returns a value; function is something that takes a bunch of inputs and returns one or more value. A method is similar but internal to a class (used in OOP - object oriented programming).

3. What is closure?

A closure is created when the inner function is somehow made available to any scope outside the outer function. Closure is function bundled together (enclosed) wtih references tol its lexical environment (surrounding state)/ Closure gives access to an outer function's scope from an inner function.

4. Describe the four rules of the 'this' keyword.

    1. GLOBAL/WINDOW BINDING: If none of the other rules apply, the 'this' keyword defaults to the window object. Unless you are in strict mode, then the case is undefined. Strict mode prevents window binding from breaking our code but will return undefined.
    2. IMPLICIT BINDING: This is the most common binding (80% of all cases). When the function is invoked, you look to the left of the dot - that's what the 'this' keyword is referring to (only applies to objects with methods).
    3. NEW BINDING: using the 'new' keyword constructs a new object and this points to it
    4. EXPLICIT BINDING:
        -call: will immediately invoke the function / ,call passes arguments in one by one
        -apply: will immediately invoke the function / .apply passes the argument in as an array
        -bind: you pass arguments in one by one but it does not immediately invoke the function; it returns a brand new function that can be invoked later.
        ALL of the above allow us to explicitly state what the 'this' keyword is in any given function.

5. Why do we need super() in an extended class?

The super() is used to call the constructor, methods and properties of parent class. You can use super() in sub classes when you want to invoke a method from the parents class when you have already overridden it in the subclasses.


## Project Set up

Follow these steps to set up and work on your project:

- [ ] Create a forked copy of this project.
- [ ] Add TL as collaborator on Github.
- [ ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [ ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [ ] You are now ready to build this project with your preferred IDE
- [ ] Implement the project on your Branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ ] Add your team lead as a Reviewer on the Pull-request
- [ ] TL then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
