# domainSense.github.io

A brief company introduction, including the company founder, a brief history, a brief product introduction, the company address, and a contact email address


# common git command

## The git clone command clones the remote repository to the local
git clone https://github.com/domainsense/domainSense.github.io.git

## View modification status
git status

## Add all changes to the staging area
git add .

## Adding specific files
git add filename

## Submit changes to the staging area to the local repository
git commit -m "提交信息"

## Check whether the address of the remote warehouse is correct
git remote -v

## Changes in the local repository are pushed to the main branch of the remote repository
git push origin main


## Use the git branch command to create a new branch. Assume that the name of the new branch is feature-branch:
git branch release-001

## Use the git checkout command to switch to the new branch
git checkout release-001


## Use the git push command to push the new branch to the remote repository:
git push origin release-001
