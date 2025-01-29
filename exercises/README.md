# Getting started with OpenTelemetry exercises

## How to use this repo
In here you will find all exercises that we created sorted in differen directories. These directories correspond with the chapters of the tutorial. So if you read the tutorial and want to start with an excercise just open the right directory.

In most directories you will find a initial and a solution directory. These contain an initial state of the application and a final state of the application. You may want to start with the initial state and if you get stuck you can look up the solution in the solution directory. Just keep in mind that you don't get a learning effect if you just look up the solution.

## How to perform the labs: The tl;dr Version
Before doing the labs, you should verify and install the following:
 - docker
 - visual studio code
	 - With the "Dev Containers" and "Docker" extensions
 - clone a local copy of the lab repo from github
 - open an instance of VS Code from the cloned directory
 - Follow the prompt to reopen in a container

## How to perform the labs: The Detailed Version
The labs in this course are designed (and have been tested)  to work using a specific set up and set of tools. In order to be able to successfully complete each exercise in this course, first ensure you have the following tools installed and configured:

 - Docker
	 - You can validate you have it running by typing `docker ps -a` at the command line.
 - Visual Studio Code (referred to as "VS Code" from here on)
 - The "Dev Containers" extension from Microsoft installed in VS Code.
	 - Installing this will also install the Docker extension.

One you've validated all the components are installed, you should
1) clone the lab exercises from it's github repo to your local machine:
[https://github.com/lftraining/LFS148-code/](https://github.com/lftraining/LFS148-code/)
2) Open a terminal window and go to the directory where the lab exercises have been cloned
3) Start a VS Code instance in that directory (usually by using the command `code .`)
	a) You will be prompted that `"Folder contains a Dev Container configuration file. Reopen folder to develop in a container"`. Click the "Reopen in container" button to proceed
	b) The first time you do this, it will take several seconds to open. This is normal.
	c) You might also see a message `"A git repository was found in the parent folders of the workspace or the open file(s). Would you like to open the repository?"` Select "Yes" to continue.
4) You are now ready to do the lab steps. Many of the actions require commands at the terminal.
	a) DO NOT USE YOUR LOCAL TERMINAL!.
	b) Instead, go to the "Terminal" menu and choose "New Terminal" and issue any commands for the lab from here.

Note that this lab environment has everything you need for each of the exercises, from languages like python and java; to an instance of docker; and more. You should not need to install anything additional. 

## How to perform the labs: The Video
For a detailed walk through with additional explanations and examples, watch this video:
[https://trainingportal.linuxfoundation.org/learn/course/getting-started-with-opentelemetry-lfs148/hands-on-lab-opentelemetry-in-action/getting-started-with-hands-on-labs](https://trainingportal.linuxfoundation.org/learn/course/getting-started-with-opentelemetry-lfs148/hands-on-lab-opentelemetry-in-action/getting-started-with-hands-on-labs)