[![Build Status](https://travis-ci.org/bast/python-tdd-exercises.svg?branch=master)](https://travis-ci.org/bast/python-tdd-exercises/builds)
[![Coverage Status](https://coveralls.io/repos/bast/python-tdd-exercises/badge.png?branch=master)](https://coveralls.io/r/bast/python-tdd-exercises?branch=master)


# Python exercises in TDD style

Inspired by:
- [Python Koans](https://github.com/gregmalcolm/python_koans)
- [46 Simple Python Exercises](http://www.ling.gu.se/~lager/python_exercises.html)
- [Programming Python for Bioinformatics](http://homepages.stca.herts.ac.uk/~comqdp1/BioInf/)


# Goal

- Fork the project.
- Login to [Travis CI](https://travis-ci.org) with your GitHub account and activate this repo for testing.
- Login to [Coveralls](https://coveralls.io) with your GitHub account and activate this repo for code coverage analysis.
- Edit this `README.md` and rename "bast" to your GitHub username or namespace (to make the badges point to your fork).
- Implement missing functions to make the unit tests pass (run tests either locally or let Travis run them for you).
- Increase the test coverage to 100% by making [all lines](https://coveralls.io/r/bast/python-tdd-exercises?branch=master) green.


# How to run tests locally (Linux or Mac OS X)

First clone the project. The unit testing
requires [pytest](http://pytest.org).

You can install it into a virtual environment:
```
cd python-tdd-exercises
virtualenv venv
source venv/bin/activate
pip install pytest
```

Then you can run the tests with:
```
py.test -vv exercises.py
```
