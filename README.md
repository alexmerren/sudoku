# Sudoku 

A playable sudoku application, including custom puzzle solving and generation algorithms. 

Contents
--------------------

 * [Requirements](#requirements)
 * [Usage](#usage)

Requirements
--------------------

This application will require quite a few dependencies to run, such as:
 * [Git](http://git-scm.com/): [This guide](https://docs.github.com/en/get-started/quickstart/set-up-git) is a good way to start.
 * [Node.js](https://nodejs.org/en/): Node is used to run the ReactJS front-end of the application.
 * [npm](https://www.npmjs.com/package/latest-version): npm is used as a package manager of node.
 * [Golang](https://go.dev/dl/): Golang is used to run the back-end of our application.
 * [Docker](https://docs.docker.com/get-docker/): Docker is used to containerise our application.

Usage
--------------------

```shell
# Clone the repository over SSH
git clone git@github.com:alexmerren/sudoku.git

# OR, clone the repository over HTTPS
git clone https://github.com/alexmerren/sudoku.git

# Go into the project directory to start the service
cd sudoku

# Run the makefile to start both the back and front-end services
make build-backend && make run-all
```
