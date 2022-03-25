# Class-4-Prompt-202

What's something that's been confusing? How would you explain it to someone else?
Calling the first vowel has been the hard for me. I would explain it to someone else by saying that they need to setup the function and then call it.

What is "use strict";? What are the advantages and disadvantages to using it?
The purpose is to indicate that the code should be executed in "strict mode".
Advantage: It makes it easier to write "secure" JavaScript.
Disadvantange: Using a variable without declaring it is not allowed.

Explain function hoisting in JavaScript.
Hoisting is JavaScript's default behavior of moving declarations to the top. JavaScript only hoists declarations. If a developer doesn't understand hoisting, programs may contain bugs or errors. To avoid errors, always declare variables at the beginning.

Explain the importance of standards and standards bodies like ECMA. 
ECMA stands for European Computer Manufacture Association. It is the association that puts out the guidelines for JavaScript in all browsers. ECMA sets a standardlized computing language like JS and it makes it user friendly.


What actions have you personally taken on recent projects to increase maintainability of your code?
I have started to become more organized so that it makes it easier to find what I need. I have tried to focus on how the tutor explains a topic. I try to practice what I learn even if I don't understand it.

Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
It's harder to ead the code and reason about it when variables seem to appear out of thin air. General code smell - if you're too lazy to put the variable only where it needs to be then what other corners are you cutting?
It’s probable that you'll encounter global variable name clashes. Since there’s only one namespace you're more likely to double up on a variable name.
