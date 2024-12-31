## List Tags Locally
To see all tags in your local repository, use:
git tag

# Delete a Tag Locally and Remotely


To delete a tag locally:

git tag -d <tag-name>
Example:

git tag -d v1.4
Delete Remotely
To delete a tag from the remote repository:



git push origin --delete <tag-name>
Example:



git push origin --delete v1.4



## What is Git Rebase
Git Rebase is a command that allows you to integrate changes from one branch into another by moving the base of your branch to a new starting point. This makes your branch history linear and easier to read.

Example:
Switch to the branch you want to rebase:

git checkout feature-branch
Rebase the feature-branch onto main:

git rebase main
If there are conflicts, resolve them, then continue the rebase
  
git rebase --continue

## Key Difference Between Rebase and Merge:

Merge keeps the original branch history with a merge commit.
Rebase rewrites the commit history to make it linear.

## To create a pull request  follow these steps:

Push Your Branch to Remote:


git checkout -b feature-branch
git push origin feature-branch
Create the Pull Request

Go to your GitHub repository: 
Click on the "Compare & Pull Request" button.
Add a title and description, then click Create Pull Request


## image 
![black  cat](blackcat.jpg)