---
layout: post
title: GSOC Update Week 1 and Week 2
excerpt: Setting up the code base.
tags: GSoC
comments: true
---

It has been two weeks since I started the project. Time for some updates.

The tl;dr version is that I have setup the project infrastructure and a little bit of code.

1. Proper `setuptools` integration. The project can now be installed with pip although the 
project is not yet available on PyPI. That will be done when I actually have something.

2. This enables us to install a command line tool by the name of `nephos`. This will be the main
frontend to interact with the entire thing.

3. Code to enable testing has been added. `pytest` will be used to test the codebase. Tests can be run via the standard
`setup.py test` command.

4. A simple config handler has been added to allow people to have config files and specify simple defaults.
Defaults will be added as and when required.

5. Google Drive interface has been added. This is the code that will finally interact with google APIs. This code
is well documented internally.

6. A few tests have also been added for this. More testing will be done soon.

7. Continuous integration has been enabled for the project. TravisCI will run tests for every commit and PR. This will
increase the reliability for every bit of code that comes by.

8. Coverage testing is done with the help of [coveralls]. This is also shown on the github page as a shiny badge.

9. Other sparkly stuff inculde checking requirement status via [requirements] and [codefactor] grading how well
code is written.

[coveralls]: https://coveralls.io/github/AadityaNair/ProjectNephos
[requirements]: https://requires.io/github/AadityaNair/ProjectNephos/requirements/?branch=master
[codefactor]: https://www.codefactor.io/repository/github/aadityanair/projectnephos
