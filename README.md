ALXprodev-advanced_git: Mastering the Git-Flow Workflow
Overview
This repository is dedicated to mastering Git-Flow, a robust branching model proposed by Vincent Driessen. Git-Flow provides a structured framework for managing code changes, which is essential for collaborative projects and scalable development. It helps teams coordinate their work on new features, production releases, and critical bug fixes in a consistent and conflict-free manner.

This project is particularly beneficial for developers working in agile and CI/CD environments, where organized and predictable workflows are key to maintaining code quality and deployment velocity.

Learning Objectives
By the end of this project, you will be able to:

Understand the core principles and structure of the Git-Flow model.

Identify the distinct roles of the main, develop, feature/_, release/_, and hotfix/\* branches.

Apply Git-Flow best practices in real-world collaborative development scenarios.

Manage the complete lifecycle of feature development, release preparation, and hotfix implementation using Git.

Learning Outcomes
Upon completion, you will be able to:

Clearly explain how Git-Flow facilitates the management of large codebases and coordinates team contributions.

Independently create and manage branches according to the Git-Flow conventions.

Execute the necessary Git commands to initiate and merge feature, release, and hotfix branches.

Integrate the Git-Flow workflow into CI/CD pipelines to automate testing and deployment processes.

The Git-Flow Branching Model
Git-Flow is defined by its use of specific, long-running, and temporary branches. The five primary branch types are:

main (or master): This branch holds the official, production-ready code. It is always stable and deployable.

develop: This is the central branch for ongoing development. All feature branches are created from develop and merged back into it.

feature/\*: When starting a new feature, you create a branch from develop (e.g., feature/user-authentication). Once the feature is complete, it is merged back into develop.

release/\*: When the develop branch has accumulated enough features for a new release, a release branch (e.g., release/v1.2.0) is created from develop. This branch is used for final testing and bug fixing before being merged into both main and develop.

hotfix/\*: If a critical bug is discovered in the main branch, a hotfix branch (e.g., hotfix/v1.1.1) is created from main. After the fix is applied, it is merged into both main and develop to ensure the fix is included in future releases.

Relevance in the Development Process
Adopting Git-Flow significantly improves:

Code Organization: By clearly separating different stages of development, it keeps the codebase clean and predictable.

Team Collaboration: The structured workflow minimizes merge conflicts and makes it easier for multiple developers to work in parallel.

Code Stability: Features are thoroughly tested and integrated in develop before they are ever considered for a production release.

Release Management: It isolates release-specific tasks, allowing the rest of the team to continue working on new features without interruption.

## The Branch in this Repo

Branch name for production releases: [master]

Which branch should be used for integration of the "next release"?

- develop
  Branch name for "next release" development: [develop]

How to name your supporting branch prefixes?
Feature branches? [feature/]
Bugfix branches? [bugfix/]
Release branches? [release/]
Hotfix branches? [hotfix/]
Support branches? [support/]
Version tag prefix? []
