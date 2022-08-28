# Branching Guide

Our branching strategy changes depending on the type of repo and the maturity of the product in production. 

We will have the following branches in this repository:

## master/main

- releasable code lives here
- merge in from feature unless its a hotfix
- this must of been reviewed by 2 developers with one being a senior

## feature/[name]

- Features (aka topics) under active development by more than one developer.
- Submit PRs here only if you've made prior arrangements to work on something in one of these branches.
- It is up to the developers creating these branches to decide what level of review is required
- These features will only ship if they are successfully pulled to master or future via the
standard PR and API review process.

## story/[name]

- Stories under active development by a developer.
- These are the branches you use to merge into feature. 
- You shouldn't be using these to merge into a release branch as a release branch would be cut from master
with the features in it
- It is up to the developers creating these branches to decide what level of review is required

## bug/[name]

- Code issues under active development by a developer.
- These are the branches you use to merge into feature branch. 
- It is up to the developers creating these branches to decide what level of review is required

## hotfix/[name]

- Code issues under active development by a developer for master/main branch.
- These are the branches you use to merge into master/main branch. 
- It is up to the developers creating these branches to decide what level of review is required
