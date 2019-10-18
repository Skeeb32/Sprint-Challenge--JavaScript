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
Both .forEach and .map are array methods. .forEach executes a provided function once for each array element and .map creates a new array with the results of callign a provided function on every element in the calling aray. Well, the forEach method doesn't actually return anything. It simplay calls a provided function an each elemment in your array. This callback is allowed to mutate the calling array. Meanwhile, the .map method will also call a provided function on every element in the array. The difference is that .map utilizes return values and actually returns a new array of the same size.

2. What is the difference between a function and a method?
A function is a piece of code that is called by name. It can be passed data to operate on an dcan opitionally return the value. In most respects, it is identical to a function expect for two key differences. A method is implicitly passed the object internal to part of a class. The term method is used almost exclusively in object oriented programming. A function is something that takes a bunch of inputs and returns one for mroe values. 

3. What is closure?
A closure is the combination of a function bundled together with references to its surrounding state (the lexical enviornment). In other words, a closure gives you access to an outer functions scope from an inner function. In JavaScript, closures are created evey time a function is created at funcation creation time. 
To use a closure, define a function inside another function and expose it. To expose a function, return it or pass it ot another function. The inner function will ahve access to the variables in the outer function scope, even after the user function has returned.
closures control what is and isn't in scope in a particualr function, along with which variables are shared between sibling functions in the same containing scope.

4. Describe the four rules of the 'this' keyword.

    1. If the "new" keyword is used when calling in the function, "this" inside the function is a brand new object. 
    2. If "apply", "call", "bind" are used to call a function, "this" inside the function is the object that is passed in as the argument. Whenever they are used as a method, "this" is explicitly defined.
    3. If a function is called as a method that is, if dot notation is used to invoke the function, "this" is the object that the function invocation, "this" is the object to the left of the dot.
    4. If the function is invoked as a free function invocation, meaning it was invoked without an of the conditions present above, "this" is the global object. In a browser, it's "window".

5. Why do we need super() in an extended class?
The "super" keyword is used in two ways. The extends keyword, and super(); function make it so trivial to bind our classes together to achieve some simple object inheritance. The extends keyword will abstract away any of the Class.call syntax that we're used to. super() is used to tell a parent's constructor to be concerned with the child's attributes vis versa and abstracts away the Object.create(this, Class) syntax. It makes the code look more cleaner at the end.

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
