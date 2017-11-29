# Docker angular-install

## Description
This is a container that run a npm install on your angular project

## Version 1.0.0
First version of docker image to help install a project, based on Angular CLI image.

## Usage
You can find the image on docker cloud ready to use: [jcbjulio/angular-install](https://cloud.docker.com/swarm/jcbjulio/repository/docker/jcbjulio/angular-install) [(source)](https://github.com/jcbjulio/angular-install)

### Run
`docker run -v <local_project_full_path>:/app jcbjulio/angular-install`
### Example
`docker run -v ~/angularProjects/my-app:/app jcbjulio/angular-install`

This will mount your project folder inside the container at location `/app` and run the `npm install` on it.

## Parent project
### [jcbjulio/angular-cli](https://cloud.docker.com/swarm/jcbjulio/repository/docker/jcbjulio/angular-cli) [(source)](https://github.com/jcbjulio/angular-cli)
To use manually the angular-cli, you can use this base image.

## Other projects
### [jcbjulio/angular-serve](https://cloud.docker.com/swarm/jcbjulio/repository/docker/jcbjulio/angular-serve) [(source)](https://github.com/jcbjulio/angular-serve)
To use it as a server just to run your project, you can use this especific image.
