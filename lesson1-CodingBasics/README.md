# Lesson 1 - Coding Basics

## What does code do?

Code acts as instructions for the computer. Each line of code acts as a specific instruction. Putting many simple, specific, instructions togather can be used to create more complex instructions. All computer programs/applications are just a bunch of these simple instructions put togather. For example, the program you are using to read this file is a bunch of these instructions combined togather to create a complex program.

## Understanding basics of code.

### Execution order.

Code in a file is executed line by line.
For example:

```python
print('Line 1')
print('Line 2')
print('Line 3')
```
OUTPUT
```
Line 1
Line 2
Line 3
```

This will always run and print in the same order. This means that when writing code, we need to be specific about the order we have the code in.

### Variables.

Variables in code are very similar to variables in math. A variable is something we can use as a representation of some data. For example, setting `a = 30` means that we can use `a` instead of `30` in our code. This is useful for many reasons. If we have a tic-tac-toe board, and lots of lines of code need to know how wide the board is, instead of using `3` everywhere, we can set `width = 3` and use width instead. Later, if we decide to make the board a 5x5 board instead, we would just change `width = 5` instead of updating `3` to `5` everywhere in the code.
Another use is for when the value may change. If we want to print the number of times an event happened, instead of `print('Event happened 2 times)` and hoping `2` is correct, we can do `print('Event happened ', numberOfEvents, ' times')`, where `numberOfEvents` is the number of times the event has happened.







