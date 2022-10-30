# Jenkins 

Jenkins is a free and open source automation server that helps automate the aspects of software development related to building, testing, and deploying.

In this repo, you can find all configuration you need in order to provide a running Jenkins server as a container, which initiate a python job on any merge request.

## How to run Jenkins container

Very simple!
All you need to do is:

1. Clone the repo to your local machine.
2. Make sure you are on the right path, that contains the docker-compose.yaml file.
3. Make sure you have docker-compose installed on your machine, else install it (https://docs.docker.com/compose/install/linux/).
4. Run the following command: docker-compose up -d 

That's it :) 

Now go to browser and try it: 
http://localhost:8080/
