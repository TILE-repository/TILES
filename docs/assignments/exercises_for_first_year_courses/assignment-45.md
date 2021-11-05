---
title: "Test Informed Learning with Examples assignment"
author:  Tanja E.J. Vos
...

# Age statistics

By [Tanja E.J. Vos](https://www.tanjavos.com).

------------------------------------------------------------------------

Python exercises used for first year programming courses that
have been adapted by using Test Informed Learning with Examples (TILE)
to integrate testing in programming education without it costing (much)
more time. The coloured boxes indicate how they were TILEd.

```testdomaintile
This colour box explains a TILE in the test domain.
```

```testruntile
This colour box explains a TILE related to test runs 
and/or test cases.
```
------------------------------------------------------------------------

# Assignment

Write a program that reads the age (an integer) of a set of people.
Data entry will end when a negative value is entered. Your program
has to calculate and display on the screen:

-   the average of the ages,

-   the maximum and minimum age, and

-   how many of them are people of working age, that is, their age
    is between 18 and 65 years old

```small
>>> %Run 
    Enter an age:50
    Enter an age:18
    Enter an age:0
    Enter an age:-2
    Average: 22.666666666666668
    Maximum age: 50
    Minimum age: 0
    People of working age: 2
>>> %Run 
    Enter an age:12
    Enter an age:16
    Enter an age:90
    Enter an age:65
    Enter an age:18
    Enter an age:17
    Enter an age:19
    Enter an age:66
    Enter an age:64
    Enter an age:-5
    Average: 40.77777777777778
    Maximum age: 90
    Minimum age: 12
    People of working age: 4
```

```testruntile
Insist that the students test their programs by giving them example
test executions.
```

# Metadata

| *Summary*                     | Calculating the age statistics. |
| *TILE aspects*                | Test domain, test cases and test run TILE-ing is applied. |
| *Topics*                      | Conditionals, arithmetics. |
| *Technology used*             | Python |
| *Audience*                    | CS1 |
| *Programming learning goals*  | Calculating statistical properties of a set of values. |
| *Testing learning goals*      | Input validation, test case design for robustness. |
| *Prerequisites*               | Basic programming constructs. |
| *Variants*                    | Many options are possible, including porting to other programming languages. |    