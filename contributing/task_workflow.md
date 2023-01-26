Adapted from RoundWorld Solutions

# Workflow Guide - Programming Tasks

Whenever you start working on a programming tasks, you should follow the general process:

## Starting a New Task
- Discuss task with functional-team (iOS or Robot teams) based on the Jira board what task to work on.
- Assign yourself all associated tasks.
- Move first task to 'in progress'.

### Starting the task
- Create a new branch, naming it after the feature you are working on. Example: `start_button`.
- You should do all of your work on this branch.

## Dev Environment

- Run `git pull` every time you being work. If there are any changes to pull down, pull them and fix any merge conflicts that might have occurred.
- While you are working, there will be updates to main, because other people will be finishing stuff as you continue working. If you are behind main when you make a pull request, you will not be able to merge it, and you will likely have merge conflicts that need to be resolved.

## Working on a task
- **MAKE SURE YOU ARE ON THE CORRECT BRANCH FOR YOUR TASK**
  - Use `git checkout` to change branches.
- Program whatever is required for the task you are working on.
- Frequently test your code.
- Do not go outside the scope of the task within the branch.

## Commit Changes
- Commit your work when it seems appropriate. Use a short message on what you implemented, for example "Implemented Start Button".
- Commits will be squashed appropriately to maintain metrics and commit history.

## Finalizing your work
When you are done working on a task, it is important to follow these steps to submit your work.

### Push Branch
- Push the working branch to the repo online. Your branch on github should mirror what you have locally.

### Create Pull Request
- Create a pull request on Github for your branch
- Move the associated task in Jira to "in-review"
- Make sure all the preliminary tests were passed
  - There should be no merge conflicts
  - Your branch should also not be behind main
- Wait for your reviewer to approve or send you comments on your pull request.
  - If approved, the reviewer will merge the PR

### If your PR is not approved
- Reproduce the issue and fix it.
- Verify that the error does not occur again before pushing.
- Push all new commits. This will update your PR.
- Message your reviewer that you have made the changes.
 
