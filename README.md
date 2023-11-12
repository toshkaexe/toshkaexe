# Welcome to Tony's GitHub Profile! 👋

## About Me

Hi, I'm Tony, a passionate software engineer with a keen interest in machine learning. Currently, I'm expanding my skills in Python and Java.

## Projects

### 1. Simple Chat Implementation

The Simple Chat Implementation is a basic chat program utilizing Java threads. It comprises three modules:

- **Client:** Employs Swing for the graphical user interface.
- **Network:** Contains classes for handling network-related functionality.
- **Server:** Includes classes for server-side operations.

[Check out the Simple Chat Implementation](https://github.com/toshkaexe/chat)

### 2. Semaphore Task and Leetcode-Tasks

#### Semaphore Task

Demonstrates the usage of semaphores, particularly in scenarios involving database operations. Find the implementation in the `semaphore_task` directory.

[Semaphore Task Implementation](https://github.com/toshkaexe/leetcode/blob/main/src/main/java/leetcode/demo/threads/SemaphoreTask.java)

#### Leetcode-Tasks

A collection of programs, functions, and tasks inspired by the LeetCode website. Explore various algorithms and solve coding problems.
[Leetcode-Tasks Implementation][Check out the project](https://github.com/toshkaexe/leetcode/tree/main/src/main/java/leetcode/demo/tasks)
### 3. Online Audiobook Player (Work in Progress)

A new project focused on creating an online player and storage for audiobooks with a bookmark function and the ability to continue listening.

[Online Audiobook Player Implementation][Check out the project](https://github.com/toshkaexe/player)

### 4. RestAPI Projects

#### Java RestAPI

A Spring Boot project for RestAPI development.

[Java RestAPI Repository](https://github.com/toshkaexe/JavaRestAPI)

#### Python RestAPI

A Python project with Flask for RestAPI development and SQLite as the database.

[Python RestAPI Repository](https://github.com/toshkaexe/PythonRestApi_React_SQL_Py3)

### 5. Data Engineering in Python

Explore and solve different problems related to Data Engineering using Python.

[Data Engineering in Python](https://github.com/toshkaexe/DataEngineer_Python)

### 6. CO2 Emission Calculator

There is a console application in JAVA returns the amount of CO2-equivalent that will be caused when traveling between two cities using a given transportation method. https://github.com/toshkaexe/co2emission In the folder staging, you will find co2-calculator.jar  This application uses rest calls to collect coordinates of 2 cities and to create a distance in km between two cities. The is important to save a token for doing rest calls for authorization at the page https://openrouteservice.org/ The API token is stored and read from an environment variable called ORS_TOKEN. GET request from: https://openrouteservice.org/dev/#/api-docs/geocode/search/get POST request from:https://openrouteservice.org/dev/#/api-docs/v2/matrix/{profile}/post

[CO2 Emission Calculator](https://github.com/toshkaexe/co2emission)

#### Example Usage:

```bash
    $ java -jar co2-calculator.jar --start Berlin --end Kassel --transportation-method=train
    Your trip caused: 2462,9kg of CO2-equivalent

    $ java -jar co2-calculator.jar --start "Los Angeles" --end "New York" --transportation-method small-diesel-car
    Your trip caused: 640313,9kg of CO2-equivalent
    
    $ java -jar co2-calculator.jar --start "Los Angeles" --end "New York" --transportation-method=large-diesel-car
     Your trip caused: 942433,8kg of CO2-equivalent
     
    $ java -jar co2-calculator.jar --start "Hamburg" --end "Kassel" --transportation-method=bus
    Your trip caused: 8409,0kg of CO2-equivalent
