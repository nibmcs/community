
# Contributing to NIBM CS


The following is a set of guidelines for contributing to NIBM CS and its packages, which are hosted in the [NIBM Organization](https://github.com/nibmcs) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)  
  * [About NIBM CS](#about-nibm-cs)

[How Can I Contribute?](#how-can-i-contribute)  
  * [Reporting Bugs](#reporting-bugs)  
  * [Suggesting Enhancements](#suggesting-enhancements)  
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)  
  * [Git Branch Naming](#git-branch-naming)  
  * [Git Commit Messages](#git-commit-messages)  
  * [Revert Commit](#revert-commit)

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

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for NIBM CS, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion and find related suggestions.

We will update these guidelines and methods once we started projects in the near future.

### Pull Requests

* After finishing the development in the feature/fix branch developer will create a pull request from github to a team specified review branch.
* Every development branch should be reviewed and approved by a code reviewer before the merge.
* Then the code reviewer can merge the development branch into the review branch.

Please follow these steps to have your contribution considered by the maintainers:

1. Follow the instructions in [the template] test_pullrequest_template
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

### Git Commit Messages

Commit messages should always be meaningful. It should express what is being changed and what type of change it is.

  * Change type of the commit message will help to identify the individual commit change-type when it was merged into the `main` branch.
  * The scope will outline which area of the application the commit will affect.

```
<type>(<scope>): <short summary>                   
  │       │             └─⫸ Summary in present tense. Not capitalized. No period at the end.
  │       │
  │       └─⫸ Commit Scope: animations|common|forms|
  |                          server|router|upgrade|
  |                          packaging|migrations|
  │                         
  │
  └──⫸ Commit Type: build|docs|feat|fix|refactor|test|chore|                    
                                                     
```

The `<type>` and `<summary>` fields are mandatory, the `(<scope>)` field is optional.


Change Types:
* docs - Only documentation changes
* build - Changes that affect the build system or external dependencies
* fix - Bug fix
* feat - New feature development
* chore - Maintenance change
* test - Adding or missing tests or correcting existing tests
* refactor - Further improvement in code base,the change is only in code level no new feature of bug fix

Valid Commit Messages ✅
* feat(account-opening) : create account opening form
* feat : create account opening form
* fix(product-definition):fix dropdown issue
* fix : product-definition fixes
* refactor(settings-engine):performance improvement

Invalid Commit Messages ❌
* changes
* new changes
* fix
* feat
* refactor
* bug fixes


### Revert Commit

If the commit reverts a previous commit, it should begin with revert: , followed by the header of the reverted commit

The content of the commit message body should contain:
  * information about the SHA of the commit being reverted in the following format: This reverts commit <SHA>,
  * a clear description of the reason for reverting the commit message.
 
 ## Additional Notes
  
 ### Issue and Pull Request Labels
  
  | Label name | Description
| --- | --- |
| `documentation` | Improvements or additions to documentation. |
| `bug` | Something isn't working. |
| `duplicate` | The issue or pull request already exist. |
| `enhancement` | New feature or request. |
| `good-first-issue` |  A good for newcomers. |
| `help-wanted` | Extra attention needed. |
| `invalid` | This doesn't seem right. |
| `question` | Further information is requested. |
| `wontfix` | This will not be worked on. |
  

