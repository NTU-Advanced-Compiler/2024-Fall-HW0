Advanced Compiler Course - Homework 0
=======

# Introduction
This homework assignment is designed to familiarize you with the Bril (Big Red Intermediate Language) project and set up your development environment. 

Bril is the intermediate representation (IR) we will be using throughout this course.

# Getting Started

1. Fork this repository

- Click the "Fork" button in the upper right corner.
- Select your account as the destination for the fork.

2. Clone your forked repository recursively to ensure you get the Bril submodule:

```=sh
git clone --recursive <url-of-your-forked-repo>
```

3. Familiarize yourself with the Bril project by reading the [Bril README](brilreadme).

# Assignment Task

Your main task for this homework is to complete the TODO in the [install_bril.sh](install_bril.sh) script.
This script is responsible for installing Bril during GitHub Actions, simulating the process you would follow on your local machine.

# GitHub Actions

The .github directory contains workflows for testing the correctness of your [install_bril.sh](install_bril.sh) script.
*Please do not modify any files in this directory*.

# Submission Guidelines

1. Complete the task in the [install_bril.sh](install_bril.sh) script.
2. Test your changes locally to ensure they work as expected.
3. Commit your changes to your forked repository:

```=sh
git add install_bril.sh
git commit -m "Completed Homework 0"
git push origin main
```

[gitsubm]: https://git-scm.com/book/en/v2/Git-Tools-Submodules
[brilreadme]: https://github.com/sampsyo/bril/tree/4029dd7b6440074bc4dd5557022848ef378f978a
