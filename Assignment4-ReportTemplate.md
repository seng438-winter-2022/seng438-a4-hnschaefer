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

TC1 - 
TC2 - 
TC3 - 
TC4 - 
TC5 - There were multiple FAQ button links followed
TC6 - There was invalid and valid inputs used for the store locater
TC7 - 
TC8 - 

# Discuss advantages and disadvantages of Selenium vs. Sikulix

Selenium
Pros:
Very easy to automate the tests
Very easy to alter values with tests that depend on them
Accepted on most major browsers
Cons:
Has problems with some types of addon/extension such as flash, shockwave
Is limited to browser testing of UI
No desktop support

Sikulix
Pros:
Scalability of visual matching (perfect to similar)
Testing is based on visual likeness, and therefore can support many more applications such as desktop and applications
Can also testing more functionality that isn't possible with script based testing (Selenium)
Cons:
More involved to setup
Does not test how we arrive at the given "visual environment"
Cannot test some functionality of scripts if there is no visual representation attached to it
Some GUI elements are not measured/captured, i.e. load times

# How the team work/effort was divided and managed
Initially we planned to divide up the work on the equally, however it became more of a group effort, with members contributing where they could, when they could. Due to lab issues and timing issues, we had to adjust our approach. Therefore as we moved through the lab, some members had larger commitments in certain areas and other areas were tackled by the remaining members.

# Difficulties encountered, challenges overcome, and lessons learned

Difficulties/Challenges/Lessons of Mutation Testing Portion

The major difficulty if the mutation testing was of course, getting the software to work. However, we also found that being aware of certain equivalent mutations was key even though it sometimes was elusive. Additionally, the PitTest plugin that we used for the mutation testing, has some quirkiness and specific concessions that you need to be aware of while using it. For example something as benign as incrementing. We found that it forced the incrementation to be post, and therefore we needed to continuously adjust the tests dependant on that functionality.

Difficulties/Challenges/Lessons of UI Testing Portion

The UI testing had a very minimal learning curve. The challenge came with verying the input to ensure good UI coverage of all of the elements. There is a difficulty that may arise such as the behaviour of UI may change depending on the traffic or other factors. Additionally, we found that there were certain elements (flash) which were not supported by the plugin we used primarily (selenium). This could cause some grief, because in order to achieve good UI coverage, you would have to search out and learn another UI testing framework. The second plugin we used, also proved to be quite a bit more involved to setup, hoever it did provide us with more options as to what it could test. We were also able to notice some tuning of the fidelity of the tests, which could allow for tolerance of the end product. This is something which could be useful depending on the scenario.

# Comments/feedback on the lab itself
This lab, when working, was a good exposure to industry tools used in GUI testing. Also we were exposed to mutation testing however there were quite a few problems with the lab content and some of were never able to get total functionality out of the lab. If the issues are worked out, this will surely be an informative lab.
