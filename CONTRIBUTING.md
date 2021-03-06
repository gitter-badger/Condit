# Condit Contributors Guide

Thanks for being interested in contributing to Condit. If you would like to contribute please email samiurkh1n@gmail.com first. 

## Setting Up
The project uses [bazel](https://docs.bazel.build/versions/master/install.html) and
[Google Test](https://github.com/google/googletest/blob/master/googletest/README.md) (for testing). To contribute, please install them.

## Compiling and Testing
Bazel handles compilation and testing with the BUILD file. 

Building a binary:
```bash
bazel build :status
```

Running a binary (for demonstrations):
```bash
bazel run :status_demo
```

Testing:
```bash
bazel test :status_test
```
Condit uses Travis CI for continuous integration and deployment. Check the state of your build [here](https://travis-ci.org/samiurkh1n/Condit). 

## Adding Documentation

Every contribution is expected to be coupled with a change to the documentation unless it is reasonably unecessary. Add documentation to the code you want to add.

## Code Review

All submissions require review. We do this using pull requests.
Learn more about pull requests [here](https://help.github.com/articles/about-pull-requests/)

## Coding Style

The project has no coding style guide for now. 
