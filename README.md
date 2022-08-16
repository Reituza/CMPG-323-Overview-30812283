# CMPG-323-Overview-30812283

## Repositories

A new repository will be created for each project below...
Project 1 2 3 4 5

## Diagram

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

The .gitignore is a text file where each line contains a pattern for files or directories to ignore. It is usually placed at the root of the project folder. Alternatively, you can put it in any folder in the repository and a project can have multiple .gitignore files.

This file lists files that are intentionally untracked and should be ignored by Git. It is important to note that changes to files that were staged before being added to the .gitignore file will continue to be tracked by Git. In other words, .gitignore will only ignore files in the working directory.
