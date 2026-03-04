# Day 03 - DevOps Final Project (using VM)

## Objective

* Combine:
	- Linux: server environment
	- Git/GitHub: code storage
	- Docker: package the application
	- GitHub Actions: CI/CD automation

## Commands Practiced

* git push origin --delete <branch_name - delete a branch 


## What I did

* Created simple web app and Dockerfile
* Built image locally and ran container
* Pushed the project folder to github
* Created workflow (yml) file and pushed
* Pulled image from DockerHub and created container
* Added paths to workflow file so that the workflow will work only when files in the specified folder are changed

## Problems Faced

* Error: non fast forward

## How I solved

* Pull and Merge:
	- git pull origin main --rebase


