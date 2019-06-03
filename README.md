# Git Workshop

Git is a distributed version control system used mostly by developers to enable collaborative work.

This workshop is inteded to provide a general understanding of Git, and recommended workflows to deal with typical use cases you'll find while working in Software Development teams.

## Dependencies

- _Git_, which you can download form <https://git-scm.com/downloads>
- _Unix-style console/CLI_ (if you are working on Windows you can use <https://www.cygwin.com/>, or install Git using the "dangerous" option)

## Git and GitHub

Github is a web service for hosting projects managed in Git. I offers additional features such as:

- Private and public repositories
- Collaborative code reviews
- Continuous Integration
- Project Management tools like issue tracking and Kanban board

You can setup you own server to host a Git repository, or choose other services like Gitlab, but these alternatives may require more exhaustive technical knowledge and setup, and you can save a lot of time, effort, and money by defauting to GitHub in most cases.

## Git authentication/security

To ma

## Git init / Git clone

```
git clone
```

## Branching

```
git checkout -b branch-example
```

## The staging area, tracked and untracked files

## Git commit

## Ammending commits

```
git commit --amend
```

## Git cherry-pick

A `cherry-pick` allows you to take the commit at the tip of a given branch and

## Git rebase

<!-- prettier-ignore-start -->
Branch A
|
|
Branch B--Commit 1--Commit 2
                      |
                      |
                    Branch C--Commit 3
<!-- prettier-ignore-end -->

## Git interactive rebase

## Rewriting history with Git

## Git stash

## Prevent loss of data

## Solving conflicts

## Tagging and Software Releases

Definition of (Tag)[https://www.thefreedictionary.com/tag]

"A strip of leather, paper, metal, or plastic attached to something or hung from a wearer's neck to identify, classify, or label..."

In Git, tags are used for a similar purpose: to mark specific commits in your repository for further reference, which is particularly useful and most generally used for (versioning)[https://semver.org/].

A nice example of this is the (**releases**)[https://developer.github.com/v3/repos/releases/] feature provided by Github, which relies in the use of tags to be used as entry point for software releases, and provides additional features like adding release notes and publish artifacts or binary files associated to the release.

More examples:

- **(React releases)[https://github.com/facebook/react/releases]** as done by the React team
- Gren: a tool to create release noteshttps://github.com/github-tools/github-release-notes

## Housekeeping

To prevent confusion both in your local environment and in your shared repository, it's a good practice to delete any branch which has already been merged to `master`, `develop`, or whatever branch being used by the team to integrate different sources of work.

## Git IDEs

Some people feel comfortable using Git IDEs like [Sourcetree](https://www.sourcetreeapp.com/)

Personally, I always prefer the console for 2 reasons:

- It requires from you to know and understand the tool you are using, which eventually gives you more power over your workflow
- If for any reason your tool fails or some problem occur, you are better prepared to solve whatever the problem is

## Testing POCs

Sometimes you have a problem that requires the implementation of several proofs of concept which are not precisely clear to define in advance, as the designed solutions themselves are hypothesis to be tested and compared later.

This may lead to costly exercises which require some setup and the documentation of some benchmark results in order to make the comparison.
