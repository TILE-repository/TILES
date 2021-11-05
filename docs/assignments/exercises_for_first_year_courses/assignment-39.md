---
title: "Test Informed Learning with Examples assignment"
author:  Tanja E.J. Vos
...

# Test Informed Learning with Examples assignment

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

Implement a program that reads 12 real numbers and calculates the
mean of the positive and negative numbers. Afterwards, the result
must be displayed to a maximum of 4 decimal places. Run the
following test cases to test your program:

**test case ID** | **inputs**                                                            |                | **expected outputs** 
------------------|-----------------------------------------------------------------------|-------------------|----------------------
                    |                                                                       | mean of positives | mean of negatives    
1                | 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12                                 | 6.5               | 0                    
2                | -1, -2, -3, -4, -5, -6, -7, -8, -9, -10, -11, -12                     | 0                 | -6.5                 
3                | 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0                                    | 0                 | 0                    
4                | 12.4, 21.005, -3.67, 4.43, 5.56, 4.2, 7, 8.3, -91.3, -1.0, 32.4, 12.1 | 11.9327           | -31.99               


```testruntile
Insist that the students test their programs by giving them example
test cases in a table. Series with only positive numbers, series
with only negative numbers, all zeros, and mix of positive/negative.
```

# Metadata

| *Summary*                     | Calculating the mean of positive and negative numbers. |
| *TILE aspects*                | Test run TILE-ing is applied. |
| *Topics*                      | Loops, conditionals, arithmetics.  |
| *Technology used*             | Python |
| *Audience*                    | CS1 |
| *Programming learning goals*  | Calculating mean of positive and negative numbers, rounding real numbers, conditionals and loops. |
| *Testing learning goals*      | Testing for robustness |
| *Prerequisites*               | Basic programming constructs. |
| *Variants*                    | Many options are possible, including porting to other programming languages. |    
