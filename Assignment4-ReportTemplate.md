**SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#4 – Mutation Testing and Web app testing**

| Group \#:       | 30  |
|-----------------|---|
| Student Names:  | Agam Aulakh  |
|                 | Melanie Nguyen  |
|                 | Heidi Schaefer  |
|                 | Jeff Roszell  |

# Introduction
In this lab, mutation testing was performed on Range and DataUtilities classes from previous labs. Mutations were injected using the Pitest plug in for Eclipse. From these mutations, we were able to design new test cases to increase coverage of the SUT. GUI testing was also performed using Selenium plug in for Google Chrome. The SportChek website was tested for bugs using record and replay functionalities of this plug in. Selenium was also compared with another GUI testing tool, Sikulix.

# Analysis of 10 Mutants of the Range class 

# Report all the statistics and the mutation score for each test class

## Data Utilities

## Range

# Analysis drawn on the effectiveness of each of the test classes

# A discussion on the effect of equivalent mutants on mutation score accuracy

# A discussion of what could have been done to improve the mutation score of the test suites

# Why do we need mutation testing? Advantages and disadvantages of mutation testing

## Why?
We need mutation testing to ensure our test cases catch faults. If source code is changed, the test result should also change.

## Advantages
- Good quantitative analysis of the quality of test suite
- Easy to identify tests to edit after receiving mutation test results

## Disadvantages
- Computationally very expensive
- Caused our IDEs to crash multiple times

# Explain your SELENUIM test case design process
TC1 - Login/Account

TC2 - Search Functionality

TC3 - Cart Functionality

TC4 - Browse Jerseys

TC5 - Viewing FAQ's
The FAQ page contains many avenues to explore. For the test purposes, we tested the button/link to shipping details and also the tracking order. As well each page would be scrolled upon to get to the apprpriate button. Then the final page was scrolled as well to ensure proper filling of all pages.

TC6 - Store Locator
The store locator takes a variety of inputs into its main objective functional query box. We decided that provind a valid and invalid input would suffice. The resulting page would be scrolled in order to ensure no bugs.

TC7 - Browse Wellness

TC8 - Triangle Rewards

# Explain the use of assertions and checkpoints

# How each functionality was tested with different test data

# Discuss advantages and disadvantages of Selenium vs. Sikulix

# How the team work/effort was divided and managed

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
