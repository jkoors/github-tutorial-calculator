# Github Tutorial Calculator

[![CircleCI](https://circleci.com/gh/GregHilston/github-tutorial-calculator.svg?style=svg)](https://circleci.com/gh/GregHilston/github-tutorial-calculator)

*Note: This repository is used for teaching purposes. Focusing on different aspects, depending on if someone wants to learn to write Python code, write unit tests or use continuous integration.*


## How To Use This Repository

This repository is to act as an example open source project to help individuals become familiar with `git` and `Github`.

The two important files are:

`calculator.py` - This file acts as the code base that would exist for an open source project. In this tutorial, the code base is a simple calculator class written in Python3. The beginning supported operations are:

* addition
* subtraction
* multiplication
* division
* square

This script isn't executable on its own, as it simply defines the above methods.

`test.py` - This file acts as the unit test that would exist for an open source project. In this tutorial, the unit tests have an example of passing (1, 1), (1, 0) and (1, -1) to each function listed above. To execute the test suite, run:

    $ python3 test.py


### How To Participate

If there is an active issue in the [issues tab](https://github.com/GregHilston/github-tutorial-calculator/issues), feel free to implement one! To do so, do the following:

1. [Fork the repository](https://help.github.com/articles/fork-a-repo/)
2. Write unit tests for your soon to be written feature, on your forked implementation
3. Write your new feature, on your forked implementation
4. Ensure your unit tests and all other unit tests pass by running them with `$ python3 test.py`
5. [Submit a pull request back to my original repository](https://yangsu.github.io/pull-request-tutorial/)
6. Wait till I review your tests and code. I'll either:
  a. Deny the request and ask you to perform some changes
  b. Accept the request, finishing off the process

As always, feel free to reach out to me on [Twitter](https://twitter.com/GregHilston). Happy coding!

_If you're experienced with writing unit tests, writing python and using continuous integration, feel free to submit for issues, encouraging others to participate in the learning activity!_


## Git

Git is a piece of version control software (vcs). What that means is it tracks the state of the project, keeping track of all files and their changes throughout history. Git is incredibly popular and most software engineer roles expect you to be familiar with it and working as a data scientist is no different.

Using git efficiently can save you countess hours and is an incredibly convenient way to ensure you code is secure and in more than one place.

Git is free and open source software distributed under the terms of the GNU General Public License version 2.


## Github

Github is a web based remote hosting service for Git. Essentially, Github is a for profit company that provides a service which provides many free tier tools for developers and enterprise level plans for businesses.

When working on a project, you should be using Git

Its important to note there are many competitors to Github, like Gitlab, which are similar. Its good to lookup the differences between sites like these. Often their free tiers differ considerably.


## Github Issues

Github issues are ways to keep track of:

* bugs
* feature requests
* enhancement requests
* any other custom labels you'd like to add

Issues can be made by not only the repository owner(s) but also the public. This makes it useful to help organize a public free and open source project.


## Forking

Forking a repository is when you take the current state of a Github repository and copy it to a repository on your own account. You would do this for a few reasons:

1. To use someone's repository as a starting point and take the project in a different direction
2. Submit a Pull Request back to the original project


## Pull Requests

Pull requests are a request one makes to have an owner of a repository to pull their work into the project. This is used a few ways:

1. To peer review colleagues' work
2. To submit a fix, improvement or any other enhancement to the project

The owner(s) will review the code and either accept the merge or request changes.


## Collaborators

Please see `COLLAB.md`
