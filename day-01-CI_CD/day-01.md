# Day 01 - CI/CD Workflow

## Objective

* Understanding CI/CD workflow

## What I did

* Pushed project files to GitHub
* Created github actions workflow (yaml)
* Pushed actions workflow
* Created docker account and initiated Docker Hub
* Added secret codes in GitHub
* Updated actions workflow for CD


## Problems Faced

* Error in yaml file
* Branch conflict: main vs. master
* CD phase, branch pushing error

## How I solved

* Corrected syntax of yaml file
* Changed branch to main
* Connected GitHub using SSH instead of HTTP

## Key Learnings

* Continuous Integration (CI): Everytime code is pushed, code is built, tests are run and docker image is built.
	- Detect errors early
* Continuous Deploement (CD): After CI passes, app is automatically deployement, and server updates itsef
	- Deliver updates automatically
