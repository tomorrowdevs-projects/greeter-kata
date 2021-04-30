## Greeter

#### Before you start:
* **Try not to read ahead.**
* **Do one task at a time. The trick is to learn to work incrementally.**

This kata demonstrates the problems of static scoped functions and objects.

All tests should always pass, regardless of environment conditions.

1. Write a `Greeter` class with `greet` function that receives a `name` as input and outputs `Hello <name>`. The signature of `greet` should not change throughout the kata. You are allowed to construct `Greeter` object as you please.
2. `greet` trims the input
3. `greet` capitalizes the first letter of the name
4. `greet` returns `Good morning <name>` when the time is 06:00-12:00
5. `greet` returns `Good evening <name>` when the time is 18:00-22:00
6. `greet` returns `Good night <name>` when the time is 22:00-06:00
7. `greet` logs into console each time it is called

## Rules and Usage
1. Initialize this project with `npm` running `npm init`
2. Install and configure `Jest` as a testing library
3. To run the tests, run `npm run test`
4. Write the code following the **TDD** (Test Driven Development) approach

## The Three Rules of TDD
1. You are not allowed to write any production code unless it is to make a failing unit test pass.
2. You are not allowed to write any more of a unit test than is sufficient to fail; and compilation failures are failures.
3. You are not allowed to write any more production code than is sufficient to pass the one failing unit test.

Which means the workflow is:

1. Write a failing test. Stop writing the test as soon as it fails.
2. Write the minimal production code required for the test to pass. Stop writing any code once the test passes.
3. Refactor the test code and the production code without altering the functionality. All tests should pass.




Before starting any of the tasks in this Learning Path, please READ the following rules
===============================

What do you need to start this Learning Path:
----------------
1. A GitHub account
3. A Local IDE or Editor
5. Git Environment
6. A http://toggl.com/ account and Chrome Extension
7. A Netlify account

Rules that you MUST follow:
----------------
- **Fork this repo into your own Github Account** as a **public** Repository
- **Create a Github Project** connected to the repository
- Read **carefully** the task description
- Analyze the task, and **create relative subtasks** to track any requirement and knowledge needed
- **Assign an estimate to each created subtask**
- Define a **deadline for the main task**
- **Provide a Flowchart within the project**
- Where required, involve other members of the community to support you on the development
- When working on a task, move it to the **In progress** column and start tracking it
- After each task completion, **move it to the "Done" column** and stop tracking it
- After the main task completion, share the solution (e.g. your GitHub repo) over the community

Following some useful materials for your work:
----------------

[Git and GitHub configuration and usage](https://www.loom.com/share/6b86aa3bc0aa4f2d88a315bc9d3209c4)

[Pseudo Code Methodology](https://wtmatter.com/pseudocode/)


