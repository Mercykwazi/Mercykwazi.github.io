---
Layout: 
Title:  "Redux"
date:   2018-06-04 09:40
categories: 
---
Four rules of simple design are the fundamental concept around software design.
Im most cases developers love to talk about good design but how make your project to be in that level is not often easy but these are the four rules that you can try and turn your project into good design

## Test pass
One of the most important thing when developing is to write test as this book also highlights the importance of test driven development.So you must ensure that automated test must pass.
It does not matter the size of your system what matters is to ensure that your automated test need to pass because at the end of the day it is not about the hugeness of your system but whether that system does work.
When writing test one needs to be careful with the test names you must ensure that your test names should influence the API that means that your system must be driven by the test that your write,writing test names that influence the Api helps to write system with less bugs or no bugs at all.
## Express intent
One of the most impotent things when writing an application is that you should be able to write code that will be able to accomodete an future changes rather that writing  a system that only answers the questions of today if the future you there is a change that once your system to accomodate you are unable then there is a problem.So one needs to write his/her varibles and functions in the manner that will be easy to identify when there is an err that is why test must be written names that correspond to what it is outh to do.
One of the importance of codebase is how quickly you can find the path that should change.
## Dont Repeat Your self(DRY)
This rule is not a rule that focuses on code duplication rather it focuses of knowledged duplication.
This principle clearly state that every piece of knowledge should have one and only one representation.it enfisise once and only once.
Before looking for code duplication you should ask your self a simple question of whether the duplication you see is an example of core knowledge in the system.
There is another type of duplication called Naive duplication this duplication is mostly mistaken to code with the same name.In the convey game of life one of the examples is when checking for the next generation,there is a rule that says any live cell with 3 live neighbors will come alive in the following generation and the other one that says any dead cell with 3 live neighbors comes to life in the next generation one may mistaken the 3 and thinks its a duplication but when you closely look at the whole code you will realise that the other one points at the dead coming to live the other states the live continuing to be alive.In order to avoid this naive duplication is that before refactoring you must give explicit names.
## Small
Once you have applied all the three rules above it is important to take a step back at your code and check whether you have written code that you wont be use.
The other thing is to look whether you have removed too much code in the name of removing duplication so you need to look back and see whether there are also other duplications that you have missed.
These four rules are inter-related in some way,when you have changed a function name of viariable name you may uncover a duplication.  
