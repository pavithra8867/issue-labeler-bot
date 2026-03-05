# GitHub Issue Labeler Bot

This project automatically labels GitHub issues using GitHub Actions.

## Features
- Automatically adds labels based on issue title
- Adds "bug" label if title contains bug
- Adds "feature" label if title contains feature
- Adds "login" label if title contains login
- Adds "needs-info" if issue has no description

## Technologies Used
- GitHub Actions
- JavaScript
- actions/github-script

## How it Works
When a new issue is created, the GitHub workflow runs automatically and checks the issue title. Based on keywords, it assigns appropriate labels.

## Example
Issue Title:
Bug: login page not working

Labels Added:
bug
login
