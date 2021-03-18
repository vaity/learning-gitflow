# Learning Gitflow 2021

## How to get started?

- Create a GitHub account if you don't have one.
- Fork this public repository to your GitHub account.
- To start working, clone your forked repository at your development system.
- Check for [issues](https://github.com/vaity/learning-gitflow-2021/issues) here tasks are created for learning purpose.
- Complete all tasks, for every task (issue) create a new branch and push your changes to that branch.

## Development Workflow

### Default Branch

master

### Branch name convention

- For feature - `feature-vt-issue-number` 
  - For example: if issue number is 3, `feature-vt-3`
- For bug - `fix-vt-issue-number`
  - For example: if issue number is 4, `fix-vt-4`

## Check Current/Active Branch
To know active branch use `git branch`

## Creating Branch OR Checkout/Changing Branch
* New branch can be created from an **active** branch, for this `git branch` OR `git checkout` command can be used.
* Create a new branch: `git branch new_branch_name` , here branch with name `new_branch_name` will be created from active branch & active branch will remain same.
* Create a new branch & checkout (change) branch: `git checkout -b new_branch_name` , here branch with name `new_branch_name`  will be created from active branch & branch will changed to `new_branch_name` , now `new_branch_name` is an active branch. 

## Deleting Branch
To delete branch use `git branch -D existing_branch_name`

## Track new files / changed files to git
* For individual file use `git add <filename>`
* For all files / folders use `git add .`

## Commiting (Saving changes) to git
* Once new files or changes added to git it can be commited to git branch using command `git commit` & option `-m` for adding commit message. `git commit -m 'Message about changes that are to be commited'`

### Pull Request (PR)
- Title should be same as Issue title, also add issue number before title. 
  - For example: if issue title is "Setup initial design" `vt-3 Setup initial design`.
- Add proper description about completed task.
- Assign reviewer for your PR.
- Create draft pull request for work in-progress (WIP) PR and don't add `WIP:` in PR title.
- PR should have one approval.
