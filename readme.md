# Introduction to docker
##  Why docker
    Docker are important for some few reasons-
        - Kubernates/Container orchestration
        - Running processes in isolated environments
        - Starting projects/services locally
## Containerization
#### What are containers
- Containers are a way to package and       distribute software applications in an way that makes easy to deploy and run consistently accross different environments.
- This allow us to package an application,along with its dependencies and libraries, into a single unit that can be run on any machine with an container runtime,such as docker

#### Why Containers?
- Everyone has different OS
- Steps to run a project vary based on OS
- Extremely harder to keep track of dependencies as project grows.

#### Benefits of containers
- Can run in isolated environments
- Helps in installing auxilary servies/DB
- Makes local setup of OS projects a breeze

### Here an simple docker command to run mongoDB locally
```sh
    docker run -d -p 27017:27017 mongo
```