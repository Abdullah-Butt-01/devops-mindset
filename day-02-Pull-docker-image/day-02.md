# Day 02 - Pull and Run Docker Image on any Server/VM

## Objective

* Simulate a deployement server
* Pull the latest docker image from Docker Hub adn run it automatically
* Understand the CD part of CI/CD

## Commands Practiced

* sudo ip addr add 192.168.56.101/24 dev enp0s8
* sudo ip link set enp0s8 


## What I did

* Logged into DockerHub
* Pulled docker image from DockerHub
* Creted container from the image

## Problems Faced

* Problem with VM, host only ip not showing
* Flask app not showing in the web
	- -p 8080:80

## How I solved

* Assigned ip manually (temporary)
	- sudo ip addr add 192.168.56.101/24 dev enp0s8
	- sudo ip link set enp0s8 up
* Port mismatched of the container and Dockerfile
	- Dockerfile: 5000
	- Container: 80
	- -p 8080:5000

## Key Learnings

* -p 8080:5000
	- first port is host
	- second port is container
