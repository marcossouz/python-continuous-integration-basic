# Continuous Integration With Python: An Introduction

When writing code on your own, the only priority is making it work. However, working in a team of professional software developers brings a plethora of challenges. One of those challenges is coordinating many people working on the same code.

How do professional teams make dozens of changes per day while making sure everyone is coordinated and nothing is broken? Enter continuous integration!


### Snapshots

#### Tests
![](https://i.imgur.com/Yru3G0k.png)

#### Lint Errors
![](https://i.imgur.com/2haZvm7.png)

#### Fix Lint Erros
![](https://i.imgur.com/hF2GRJj.png)

#### Run Tests CircleCI
![](https://i.imgur.com/kavbS7c.png)


### Table of Contents

- [x] 1. What Is Continuous Integration?
- [x] 2. Why Should I Care?
- [x] 3. Core Concepts
    - [x] 3.1 Single Source Repository
    - [x] 3.2 Automating the Build
    - [x] 3.3 Automated Testing
    - [x] 3.4 Using an External Continuous Integration Service
    - [x] 3.5 Testing in a Staging Environment
- [x] 4. Your Turn!
    - [x] 4.1 Problem Definition
    - [x] 4.2 Create a Repo
    - [x] 4.3 Set Up a Working Environment
    - [x] 4.4 Write a Simple Python Example
    - [x] 4.5 Write Unit Tests
    - [x] 4.6 Connect to CircleCI
        > Our pipeline is very simple and consists of 3 steps:
        > - Checking out the repository
        > - Installing the dependencies in a virtual environment
        > - Running the linter and tests while inside the virtual environment
    - [x] 4.7 Make Changes
    - [x] 4.8 Notifications
- [x] 5. Next Steps
    - [x] 5.1 Git Workflows
    - [x] 5.2 Dependency Management and Virtual Environments
    - [x] 5.3 Testing
    - [ ] 5.4 Packaging
    - [ ] 5.5 Continuous Integration
    - [ ] 5.6 Continuous Deployment
- [x] 6. Overview of Continuous Integration Services
- [x] 7. Conclusion


### References

- https://realpython.com/python-continuous-integration/
