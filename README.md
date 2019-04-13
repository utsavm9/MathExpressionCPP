# Math Expression Simplifying Program

## Project Description

This program is a term rewriting program which repeatedly applies all the available rules to the expression being simplified. The rules are maintained in a rule  book, which can be edited by the user. The program also comes with the capabilities of allowing the user to add and delete rules. 

A sample run of the program is presented here. The user just entered `d/dx(d/dx(x^3))` and the program showed the simplified result of ![equation](https://latex.codecogs.com/gif.latex?\frac{\mathrm{d}}{\mathrm{d}x}\frac{\mathrm{d}}{\mathrm{d}x}x^3)

![Sample image of the program](https://github.com/utsavm9/MathExpressionCPP/blob/master/sampleImg.png)

## Getting started 
This program is designed to run on TurboC++ compiler and has been tested to run successfully on compiler version 3.2. Download the Turbo C++ compiler from [its website.](https://developerinsider.co/download-turbo-c-for-windows-7-8-8-1-and-windows-10-32-64-bit-full-screen/)

Then, move the files inside the `program` folder inside the `bin` folder located in the Turbo C++ directory, which is by default in `C:` for Windows users. The program can then be opened and run inside the Turbo C++ IDE.

## File Information
* `MATH.CPP` contains the program

## Solution Implementation
The algorithm implemented for expression re-writing is based on matching and replacing parts of expressions. Numerous functions use several algorithms to achieve their task and some of noteworthy techniques are presented as follows:

* Dijsktra’s shunting yard algorithm for conversion into postfix
* File manipulation: creating, deleting, writing, appending, traversing
* Recursive function for calculating HCF
* Push and pop operations on a stack
* Window-like user interface with enter-less input functionality
* Pausing bulk writing on screen when text content start to move out of view
