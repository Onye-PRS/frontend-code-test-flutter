# Onye frontend test
This is a test for new candidates joining Onye. It is meant for developers that will be working on the frontend of the Onye platform.

Read this entire readme before you start coding.

The repository contains this readme and a docker compose file that will allow you to run the backend you will be building a frontend for.

The backend will be running on port 8080 by default hence you will be able to access it on http://localhost:8080/ once you are running the docker container.

The test should take you no more than 2-3 hours to complete.

### How to perform the test
Checkout this repository to your local machine and complete the tasks described below. When you are done send the code to us in a zip-file or a link to your private repository.

### How you will be judged
We will be primarily looking at code quality and structure. Do not focus solely on providing solutions, focus more on scalability. Will your code be extendable and scalable?

It is better to not complete all tasks but have good code structure and quality than to complete all the tasks and have a "bad" solution.

# Test tasks
The test consists of three tasks. Complete as many as you can.

### Task 1
Build a simple login page in Flutter and connect it to the backend.

### Task 2
Build a simple page that will simply display user information from the home controller.

### Task 3
Do a redirect that will load the user info page upon login (combining task 1 and 2).

# Running the backend application
    
### Start:
    docker-compose up

### Tear down:
    (run Ctrl+C to kill)
    
    docker-compose down -v

# Prerequisites
- Docker
- Docker Compose