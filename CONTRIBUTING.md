# Contributing to NIBM CS



The following is a set of guidelines for contributing to NIBM CS and its packages, which are hosted in the [NIBM Organization](https://github.com/nibmcs) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [About NIBM CS](#atom-and-packages)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Branch Naming](#git-branch-naming)
  * [Git Commit Messages](#git-commit-messages)
  * [Documentation Styleguide](#documentation-styleguide)

[Additional Notes](#additional-notes)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels)


## Code of Conduct 
This project and everyone in it is goverened by the [NIBM CS Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [nibmcs.contact@gmail.com](mailto:nibmcs.contact@gmail.com)

## What Should I Know Before I Get Started

### About NIBM CS 
We, NIBM Computer Society are mainly divided into 3 clubs which are NIBM Code Labz, NIBM Mozilla Campus Club and NIBM FOSS Community. Now, let's all come together and rebrand as the NIBM Computer Society. Our mission as a campus society is to build a strong network among the students of the School of Computer Science and allow them to gain more knowledge and share it with others.


## How Can I Contribute 

### Reporting Bugs

This section guides you through submitting a bug report for NIBM CS. These guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports 

We will update these guidelines and methods once we started projects in the near future. 

### Suggesting Enhancement 

This section guides you through submitting an enhancement suggestion for NIBM CS, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion and find related suggestions.

We will update these guidelines and methods once we started projects in the near future. 

### Pull Request

* After finishing the development in the feature/fix branch developer will create a pull request from github to a team specified review branch.
* Every development branch should be reviewed and approved by a code reviewer before the merge.
* Then the code reviewer can merge the development branch into the review branch.

Please follow these steps to have your contribution considered by the maintainers: 

1.Follow the instructions in [the template] 
2. Follow the [styleguides](#styleguides)

## Styleguides 

### Git Branch Naming 

Change type is used to easily identify the change type which is contained in the branch itself. (This will ease the life of code reviewers and module owners)

Description is an optional for the branch name.It will further improve the identifiability of the branch.

Branch should be created with this format:
[change-type]-[description]

Change Types:
* fix - bug fix
* feat - new feature development
* chore - Maintenance change

Valid Branch Names ✅
* feat-account-opening
* fix-popup-opening-issue

Invalid Branch Names ❌
* FXL-123
* account-opening-feature
* bugFixses

