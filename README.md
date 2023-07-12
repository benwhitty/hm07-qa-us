# Sprint 7 project 

The tasks of this project consist of completing 5 tasks and writing tests for GET, POST, PUT, and DELETE requests as well as creating a README.md file used for describing principles, that I have used to write code.

 # What information does this file contain?

 The purpose of this file was used for describing principles, that I used to write code.
The main idea is that I have formulated my code to be readable for others. 

# Tasks of the project

- *Tasks 1-4: Tests for GET, POST, PUT, and DELETE requests*
In each of these tasks, we need to choose one endpoint from the Urban Grocers documentation and write at least two tests: 
- Check the response status code
- Parse the response and check that the response body contains the expected data
- *Task 5 was to create and add a README.md file* 

# Resources used throughout the completion of the project

- Swagger to check endpoints
- Postman to build and test the APIs
- Command Prompt as the default command-line interpreter for Microsoft Windows (the operating system of my laptop)
- VS Code of course to edit, build, and debug tests for the tasks of this project

# Instructions on how to configure resources used for testing

- *Step 1: Connect your GitHub*
The first step was to link my GitHub account to Practicum. To do so, I clicked the "Link GitHub account" button in the widget at the top of this page. This took me to a new browser tab where I was asked to confirm that I wanted to link your GitHub account. Upon confirming, my Practicum profile was connected to to my GitHub profile via GitHub's secure API. This allowed me to submit my projects automatically at the click of a button, directly within the Practicum platform.

- *Step 2. Clone the repo to your computer*
Once I linked my Practicum account with GitHub, a repository was created automatically. The repository name was be hm07-qa-us.
I then went to GitHub and cloned the new repo to my local computer, using the following steps:
Open your preferred terminal emulator. If you’re on Windows, use Git Bash (I am on windows).
If you haven’t done so already, create a directory to store all of your projects. For example:
 cd ~               # make sure you're in your home directory
 mkdir projects     # create a folder called projects
 cd projects        # change directory into the new projects folder
  
Clone the repo. The command you use will depend on the authentication strategy that you’re using.
 # if you are using HTTPS
 git clone https://github.com/username/hm07-qa-us.git
 
 # if you are using SSH
 git clone git@github.com:username/hm07-qa-us.git
  
💡 Make sure that you clone the correct repo. I chose SSH, and the username should be your own username, not practicum-com.

- *Step 3. Work with the project locally*
Now I have a local copy of the project and can open the project folder on my computer.
Before starting your work with the project, run npm install from the console in your project folder.
💡 When working on the project locally, you can use a standard text editor, but I recommend using VS Code. Simply open VS Code and select File → Open Folder and then select the hm07-qa-us folder that you cloned to your computer.

In config.js, replace the API URL with the unique link generated after the launch of Urban Grocers server. We will use this variable to store the API URL. It helps us to declare the URL in one place and then use it throughout the whole project.
When you’re ready to start working, hit the “start server” button to get your server URL.
Great, your server is on!

For your convenience, please open the link in a new tab.
Server address: https://f8ec3e8a-ed7d-4bbb-a630-7e04f3c8f8e9.serverhub.tripleten-services.com
Remember, you can use Swagger: URL /api/swagger to check the endpoints.
Once you’ve completed the steps above, you’re ready to work on the tasks.

- *Step 4* Write README.md
In this task, we need to add a README.md file to the root directory of our project. The README should include the project’s name, a description of the project, a description of the technologies and techniques used, and instructions on how to run the tests. I have just done this! 

# Instructions on how to run tests

😎 The minimum requirement for tasks 1–4 is 2 tests for a single endpoint. However, if you want to really show off your skills, you have the option to write additional tests and use additional endpoints for those tests. I chose to only use 2 tests per task.

- *Step 1* Select an endpoint from Urban Grocers API Documentation (Swagger) and Run postman to test API 
Assign a variable to your Urban Grocers Server URL for efficiency and choose one endpoint from the API documentation (Swagger) to run your tests. These will be different since you will test GET, POST, PUT, and DELETE requests. 

- *Step 2* Input your test data into VS Code under each corresponding test and run the test npx jest tests/your request/Handlers.test.js into the Command line
💡 It’s possible you will find bugs in the API endpoints. For example, if an endpoint returns 504 instead of 400, you may have found a bug. The important part (for these tasks) is that you are able to create code that can query the endpoints.