# How to ensure the quality of a software system(a management system) #
The Homework for Week 8 By Feng Xiangmin (冯祥敏13126069, Email:minxinfeng#gmail.com(# for @)) From Group C.

Based on what we'velearned from the course, design how to ensure the quality of a software system. I choose the web application I have involved in(a management system) for example, but not for detail.

Software quality assurance (SQA) consists of a means of monitoring the software engineering processes and methods used to ensure quality.SQA encompasses the entire software development process, which includes processes such as requirements definition, software design, coding, source code control, code reviews, software configuration management, testing, release management, and product integration. SQA is organized into goals, commitments, abilities, activities, measurements, and verifications.

1. Test early and often
Where possible quality should be built in throughout the development life cycle rather than tested in at the end of a project. This is an important part of the agile development process which we use when making our apps. We test what we do, whether it’s design, code, or documentation, early and often so that defects are found while the work is still fresh in people’s minds and before the defects can become too deeply embedded in the software.

2. Test Smarter to Test Less 
It can reduce defects. A focus on testing the most crucial and at risk areas ensures that they receive the lion's share of test resources and that any bugs that slip through are likely to be confined to the least-important features. 

3. Minimise variation
Any customisation of the software introduces variation which needs to be tested and maintained for every version of the app. Lean manufacturing has taught us that by minimising variation and developing apps which work for people out of the box we can reduce costs and more thoroughly test what we make, increasing the value of what we do for our clients. We recommend to our clients that they avoid paying us to customise our apps when possible so that we can provide them with the most cost efficient solution.

4. Build in flexibility
Where there is a common need for the same customisation from lots of clients we try to allow for this by building flexibility into the system. This limited and known variation can be accounted for when testing and does not add a huge cost overhead to our development process, while at the same time allowing our clients to change the things they need to.

5. Functional testing

- Ensure every line of code executes properly with Unit Testing: Function coverage & Statement coverage & Path coverage.

- Ensure every function produces its expected outcome with Functional Testing. It concerns surrounding the correct implementation of functional requirements, usually using black box testing.

- Ensure all functions combine to deliver the desired business result with System Testing. It executes end-to-end functional tests that cross software units, helping to realize the goal of ensuring that components combine to deliver the desired business result. 

- Ensure new changes did not adversely affect other parts of the system with Regression Testing. It ensures code modifications have not inadvertently introduced bugs into the system or changed existing functionality. Goals for regression testing should include plans from the original unit, as well as functional and system tests phases to demonstrate that existing functionality behaves as intended.

- Ensure the system integrates with and does not adversely affect other enterprise systems with System Integration Testing. It is a process that assesses the software's interoperability and cooperation with other applications. 

- Ensure the customer is satisfied with the system with Acceptance Testing. It aims to test how well users interact with the system, that it does what they expect and is easy to use. 









