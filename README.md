
# qa-automation-learn
This repository contains learning materials for QA and SDET. In this repo I will provide the materials from basic things of programming to next things such as  frameworks, tools and library. Please learn the whole thing in order so you can fully understand and learn the next things properly.

**Outline**

     1. Learn the basic of GIT workflow
     2. Learn the basic of scripting and programming language
     3. Automation framework and Library (API, UI)
     4. BDD Testing
     5. BDD Testing framework


## Learn the basic of GIT workflow
in order to work with code and contributing within a team, we will need git to make our work easier, git is used for source code management. To understand how git work and why we need it, let me give you some example case and simple analogy:

Let's imagine you are working on a single document with your friends for a 3 people of group assignment, this document is going to be submitted to your teacher tomorrow, so you and your friends are working on them today, but unfortunately you two are seperated and cannot work together in a same place. So you and your friends divide tasks for each member.
A (you): is working on document,
B: is working on document, 
C: Having 1 master document with version number, receiving updates from A or B whenever they give C an update for the document and merge the updates to master document and give version for each merge. So they have this flow of working:

- C: Holds a master documents. give a copy to A and B at initiation.
- A: Write a title 'assignment of group ABC' on his document -> send it to C
- C: receive update from A then write it to master document, sign it with 'version 1' , and make announcement that there are updates to master doc.
- A: since the master is updated then A has to get latest master doc from C (basically every updates on master document, A and B have to get the latest document from C before continuing their work or sending update to C so their current document is always relevant, make sense right?), then he is working on the doc again. 
- B: in the middle of working, he's got the announcement of the update of master doc, so B has to get the latest update to, then he get it. Then B kinda make an addition to the title and change it to ''group assignment of group ABC" he added 'group' to the title, and add group members details under the title 'A,B,C' then he send it to C. C receive the update and merge it to master document, sign it with 'version 2', and make announcement that there are updates to master doc. Then A and B receiving the announcement of the updates and get the latest master doc (version 2) nad continuing their work again.

the iteration is going over and over again until tomorrow.

well, above is just a simple analogy to understand why we need git and how it works, there are more terms in git workflow such as: 
commit, pull, push, fetch, rebase, reset, etc. you can learn git in this interactive playground: https://learngitbranching.js.org/




## Learn the basic of scripting and programming language

in order to learn automation tools we need to have a basic understanding of scripting and programming language. What is the differences between them? 
a scripting language is interpreted, and programming language needs to be compiled to machine code so as to run them on the hardware of an underlying OS (operating system), to learn about then in details go to here: https://www.geeksforgeeks.org/whats-the-difference-between-scripting-and-programming-languages/

In this learning, we will use two language: javascript and python. Learn here:
 - Javascript: https://playcode.io/
 - python: https://www.learnpython.org/



## Automation framework and Library (API, UI)
In this repo, I will give and examples of automation framework for API and UI testing that is most relevant and trending these days and most companies and organization use them, there are bunch of other framework, tools, and libraries out there. You can learn it as well by yourself.


### API test: 
 - Mocha.js https://mochajs.org/

### UI automation web: 

 - katalon: https://katalon.com/
 - https://webdriver.io/
 - cypress: https://www.cypress.io/
 - robot framework: https://robotframework.org/, robot framework using selenium library to interact with browser:https://robotframework.org/SeleniumLibrary/SeleniumLibrary.html
 
### UI automation mobile: 

 - https://webdriver.io/
 - robot framework using appium library to interact with mobile app: https://docs.robotframework.org/docs/different_libraries/appium,
 - https://medium.com/zenjob-tech-blog/webdriverio-with-appium-beyond-the-perfect-scenario-b534aa70c84e

## BDD Testing
**Behavior-driven development** is a testing practice that follows the idea of specification by example (e.g., Test-Driven Development [TDD]). The idea is to describe how the application should behave in a very simple user/business-focused language.
refer to this reference:
https://katalon.com/resources-center/blog/bdd-testing


## BDD Testing Framework

https://www.browserstack.com/guide/learn-about-cucumber-testing-tool
 - Cucumber: https://cucumber.io/

