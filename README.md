# branchingGitFlow
This branch is to demonstrate various git branching techniques 

**What is a Branching Strategy?**
A branching strategy is a systematic approach to managing your Git Repository’s branches. ​

It defines how branches are created, used, and merged, ensuring teams maintain order
and efficiency throughout the Git Life Cycle. ​

Ensure smooth collaboration and organized code​
Provides clear rules for writing, merging and deploying code.​
Helps keep the repository structured and maintainable.​
Reduces merge conflicts when multiple developers work simultaneously.

# GIT Flow Workflow
GitFlow enables parallel development, allowing developers to work separately on feature branches. ​

A feature branch is created from a master branch and after completion of changes the feature branch is
merged with the master branch.​

**Master:** Used for product release
​
**Develop:** Used for ongoing development
​
**Feature Branches:** Created from the develop branch to work on specific features.​

**Release Branches:** Created from the develop branch to prepare for production releases and bug fixes​

**Hotfix Branches:** Created from the master branch to address urgent issues directly in production. It
helps in addressing discovered bugs smoothly, allowing developers to continue their work on the
develop branch while the issue is resolved.

**Note:** The Master and Develop branches are the main branches that remain throughout the journey
of the software. The other branches are supporting branches and are short-lived that serving
specific purposes.
