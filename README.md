# CMPG-323-Overview-30812283

## Repositories

A new repository will be created for each project below...
Project 1 Agile and Scrum
Project 2 API development
Project 3 Standards and Patterns
Project 4 Testing and RPA
Project 5 Power BI

## Diagram

<div style="display: flex; justify-content: center;">
    <img src="https://mfdot.com/AboutMe/Diagram.drawio.svg" alt="" style="width: 500px ;height:300px">
</div>

## Branching strategies

The Branching strategy i will be using is GIT FLOW
This branching strategy consists of the following branches:
Master 
Develop
Feature- to develop new features that branches off the develop branch 
Release- help prepare a new production release; usually branched from the develop branch and must be merged back to both develop and master
Hotfix- also helps prepare for a release but unlike release branches, hotfix branches arise from a bug that has been discovered and must be resolved; it enables developers to keep working on their own changes on the develop branch while the bug is being fixed.
The main and develop branches are considered to be the main branches, with an infinite lifetime, while the rest are supporting branches that are meant to aid parallel development among developers, usually short-lived.

## Uses of gitignore

When a Git project is compiled it may generate binary files, lock files, temporary files and metadata files. These are intermediate files that are not part of the source code. For example, IDE config files or intermediate files like “.class”,”.exe”, “.bin” etc. that are generated during compilation should be ignored by the version control system as they will be different for each developer machine and will unnecessarily increase the size of the repository.


## storage of credentials and sensitive information
It is important to store sensetive information because extensive code re-use increases the risk of distributing vulnerabilities from one dependency or repository to another.

To save credentials you can clone Git repository by setting a username and password on the command line:
$ git clone https://<USERNAME>:<PASSWORD>@github.com/path/to/repo.git

Save Username and Password in Git Credentials Storage
Run the following command to enable credentials storage in your Git repository:

$ git config credential.helper store
