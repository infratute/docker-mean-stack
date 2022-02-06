# Dockerize MEAN Stack Application
docker-mean-stack

__This project tops the mean-stack application project, with aim to dockerize the mean-stack app.__

> For the mean-stack project refer to - 'https://github.com/infratute/mean-stack.git'

After having successfully tested the MEAN stack application on your local machine, create the following:

1. Dockerfile within the mean-stack directory
2. Dockerfile within the client directory(mean-stack > client)
3. dockerfile.yml file within the mean-stack directory.

The relevant files have been added here.

Ensure you are within the mean-stack directory.

```
cd mean-stack
docker-compose build
```
Now run:

```
docker-compose up
```
The above command will start all the containers and display the console logs.

You may choose to run 
```
docker-compose up
```
to run the containers in a detached mode. In this mode the logs are not visible and you will require to use the logs to view the console.

