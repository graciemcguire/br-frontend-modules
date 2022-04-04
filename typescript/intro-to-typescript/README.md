# Introduction to TypeScript

## Learning Goals

- Understand TypeScript at a high level
- Explain some of the benefits of using TypeScript when developing web applications

## Introduction

If you've ever worked with JavaScript, you've undoubtedly run into bugs that took
what felt like forever to find the root of, weird errors, or lack-there-of,
(Looking at you, `'undefined' is not a function`), and cursed the JavaScript gods
for allowing such problems to always happen. If this sounds familiar, then
TypeScript may be the answer to your curses.

A superset of JavaScript, TypeScript was created by Microsoft in 2012 to help
developers write code, and catch errors and bugs quickly and efficiently. This
allows developers like you to put your energy and focus towards designing a good
experience for end users of the application.

In this lesson, we will discuss what exactly TypeScript is and why it is so
awesome and useful.

## TypeScript Overview

In a study done for the [2021 State of JS][], 69% of the developers polled said
they preferred to use TypeScript as their JavaScript compiler, and in the Github
study, [Top Languages Over The Years][], TypeScript came in as the #4 most
popular language for 2 years in a row! (2020-2021)

[Octoverse - Top Languages Over The Years 2021 Image]('https://curriculum-content.s3.amazonaws.com/blackrock/intro-to-typescript/top-languages-used-2021.png')

As mentioned above, TypeScript is a superset of JavaScript... so what does that
mean? A superset expands and elaborates on all the parts of a language, while
still fully encompassing the entirety of the original language.

Think about JavaScript before ES6. If you were writing a program in ES5 or
before, and tried to use `const` to declare a constant variable, it wouldn't
work, right? But if you were writing your program using ES6 and wanted to go old
school and use `var` to declare your constant variable, it would still work, but
you would be opening your code up to a lot of potential bugs in the future. The
same idea goes for TypeScript. We can write regular JavaScript code into a
TypeScript file and it will work fine, but by using TypeScript it will work a
whole lot better, and save us a lot of debugging and hair-pulling down the line.

TypeScript builds onto JavaScript by adding type-checking and type
declaration abilities for all different data-types, classes, and other
object-oriented features through its type system.

By declaring types, we can write extremely explicit JavaScript code by
telling our program what type of datatype a variable should be, what a function argument
should be, what our arrays will contain, and more!

By using this type system and the TypeScript compiler, TypeScript is able to
easily highlight and unexpected behaviors in our code, taking most of the guess
work out of debugging!

## TypeScript 

## React Overview

React is built entirely out of JavaScript, using a combination of dependencies.
Using React might seem significantly different from what you're used to when
writing vanilla JavaScript (or, in other words, just JavaScript). This is
because React provides a specific way to organize and structure the design of a
web application.

Using JSX, an extension of vanilla JavaScript with a specific syntax, we can
write code that looks very similar to HTML. Snippets of this JSX get separated
out into components, sort of like building blocks.

When combined, these components form a fully working web application. The use of
components lets us separate code and functionality in a logical and easy to read
way, producing highly reusable, independent, chunks.
...

## Some of the Awesome Features of TypeScript

From the [TypeScript docs][], here are four of the key features of Types in TypeScript:

- **Type by Inference**
- **Defining Types**
- **Composing Types**
- **Structural Type System**

Let's dig into each of these features and talk a bit more about each one.

## The Other Thing

...

## Conclusion

...

## Resources

- [2021 State of JS]('https://2021.stateofjs.com/en-US/other-tools')
- [Top Languages Over The Years]('https://octoverse.github.com/#top-languages-over-the-years')
- [TypeScript docs]('https://www.typescriptlang.org/docs/')
