
# QA Automation Learn
This repository contains learning materials for QA and SDET. In this repository, I will provide materials covering basic programming concepts and progress to more advanced topics, including frameworks, tools, and libraries. 
**Please follow the learning sequence to gain a comprehensive understanding and effectively learn the subsequent topics.**

**Outline**

    1. Learn the basics of GIT workflow.
    2. Learn the basics of scripting and programming languages.
    3. Automation frameworks and Libraries (API, UI).
    4. BDD Testing.
    5. BDD Testing frameworks.

## Learn the Basics of GIT Workflow
To work with code and contribute within a team, Git is essential for efficient source code management. To understand how Git works and why it's necessary, consider the following example:

Imagine you are collaborating with friends on a group assignment involving a single document. This document needs to be submitted to your teacher the following day. However, you and your friends are located separately and cannot work together in the same place. To manage this, you divide tasks among team members.

A (you) works on the document.
B works on the document.
C holds a master document with version numbers, receives updates from A or B, merges the updates into the master document, and assigns a version number for each merge. Here's the workflow:

- C initially holds the master document and provides copies to A and B.
- A writes the title "Assignment of Group ABC" on their document and sends it to C.
- C receives the update from A, incorporates it into the master document, labels it with 'Version 1,' and announces the updates to the master document.
- A, since the master document is updated, needs to obtain the latest master document from C before continuing their work. This process ensures that their document is always relevant. A then resumes working on the document.
- B, in the middle of working, receives an announcement of a master document update. B obtains the latest update, adds 'group' to the title, and includes group member details under the title 'A, B, C.' B then sends it to C. C receives the update, merges it into the master document, labels it as 'Version 2,' and announces the updates to the master document. A and B receive the announcement of the updates and retrieve the latest master document (Version 2) to continue their work.

This iteration continues until the deadline. In this analogy, A represents you, working as part of a team contributing to code, B represents your teammate, and C represents Git. Various Git remotes, such as GitHub, GitLab, and Bitbucket, are essentially the same, offered by different companies. It's important to note that Git remotes are necessary to store code on remote servers (e.g., GitHub, GitLab) for team access.

This simple analogy helps illustrate why Git is needed and how it works. Git involves various terms, including commit, pull, push, fetch, rebase, reset, and more. You can learn Git in an interactive environment at [Learn Git Branching](https://learngitbranching.js.org/).

## Learn the Basics of Scripting and Programming Languages
To learn automation tools, you need a fundamental understanding of scripting and programming languages. What distinguishes them?

A scripting language is interpreted, while a programming language requires compilation into machine code to run on the hardware of an underlying operating system (OS). For detailed information, you can explore the differences [here](https://www.geeksforgeeks.org/whats-the-difference-between-scripting-and-programming-languages/).

In this learning journey, we will use two languages: JavaScript and Python. You can learn them here:

- JavaScript: [PlayCode](https://playcode.io/).
- Python: [LearnPython.org](https://www.learnpython.org/).

## Automation Frameworks and Libraries (API, UI)
In this repository, I will provide examples of automation frameworks for API and UI testing that are highly relevant and popular in today's industry. Many companies and organizations use these frameworks, tools, and libraries. You can also explore additional options independently.

### API Testing:
- [Mocha.js](https://mochajs.org/)

### UI Automation (Web):
- [Katalon](https://katalon.com/)
- [Webdriver.io](https://webdriver.io/)
- [Cypress](https://www.cypress.io/)
- [Robot Framework](https://robotframework.org/), which uses the Selenium library for browser interaction: [SeleniumLibrary](https://robotframework.org/SeleniumLibrary/SeleniumLibrary.html)

### UI Automation (Mobile):
- [Webdriver.io](https://webdriver.io/)
- Robot Framework, using the Appium library for mobile app interaction: [Appium Library](https://docs.robotframework.org/docs/different_libraries/appium)
- [WebdriverIO with Appium](https://medium.com/zenjob-tech-blog/webdriverio-with-appium-beyond-the-perfect-scenario-b534aa70c84e)

## BDD Testing
**Behavior-driven development (BDD)** is a testing practice that follows the concept of specification by example, similar to Test-Driven Development (TDD). BDD focuses on describing how an application should behave in a user and business-focused language. For more information, refer to this [resource](https://katalon.com/resources-center/blog/bdd-testing).

## BDD Testing Framework
Learn about the Cucumber testing tool at [BrowserStack](https://www.browserstack.com/guide/learn-about-cucumber-testing-tool).

- [Cucumber](https://cucumber.io/).
