# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days..

You are not allowed to collaborate during the sprint challenge. 

_You have **three hours** to complete this challenge. Plan your time accordingly._


## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead as the evaluate your solution.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. Briefly compare and contrast `.forEach` & `.map` (2-3 sentences max)
-The main difference between .forEach and .map is that the latter will create a new array with the result. the .forEach method will ALTER THE ORIGINAL DATA, so it is highly advised not to use that method in the real world, or at all really, because original data sets should always be protected unless approved or the goal is to change that data itself. 

2. Explain the difference between a callback and a higher order function.
- A higher-order function allows us to pass functions as a parameter to other functions. Essentially, allowing us to call functions in different areas all over the execution stack. Callbacks are functions that are "called again |or| 'back'" within the same function as a paramter to return a result after the variable is defined within the function itself (as opposed to in another function completely like a higher order function, and then THAT function is passed as an argument in another function entirely.). 

3. What is closure?
- Close is what "finishes" or "closes" a function's process. It is commonly mistaken as "what is enclosed within scope" of a function - but it is not - it is another function or callback in the execution stack that "closes the process" to another function. 

4. Describe the four rules of the 'this' keyword.
- Global binding - this binds .this to the global window and is usually bad practice.
- Implicit binding - .this IS the OBJECT that 'owns' the code, when you use .this, it is referring back to the parent that it is within, it INHERITS it's features/keys/etc.
- New binding - the value of .this when used in an object is the OBJECT ITSELF
- Explicit Binding - creates a NEW function, with the .this binding as the new function's name.

5. Why do we need super() in an extended class?
It makes the child inherit the parent's base features when using an 'extend' from the parent. it creates a new object, using the parent's features, and then you can add on different functions to customize that child in different ways from the parent. Such as family inheritance examples. A child with super() will inherit the parent's hair and eye colors that are set, and then the child could have a seperate function of their personal interest that makes them different; except for the features inherited from the parent. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set Up

Follow these steps to set up your project:

1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test:watch` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Task 2: Project Requirements

Your finished project must include all of the following requirements

#### Task A: Closure

This challenge takes a look at closures as well as scope. 
* [ ] Find this challenge in the index.js file. Read the instructions carefully!

#### Task B: Objects and Arrays

Test your knowledge of advanced array methods and callbacks.
* [ ] Find this challenge in the index.js file. Read the instructions carefully!

#### Task C: Prototypes

Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Find this challenge in the index.js file. Read the instructions carefully!

#### Task D: Classes

Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* Find this challenge in the index.js file. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

### Task 3: Stretch Goals 

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements! Please remember to comment out your stretch goals before you submit 

## Submission format

See Canvas for submission instructions 

