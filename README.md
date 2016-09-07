# cmpe273-lab1
The purpose of this lab is to setup a Docker enviroment for CMPE-273 class and understand the Flask micro webservice-framework for Python.

Steps :
1) Install docker https://docs.docker.com/engine/installation/#/on-osx-and-windows
2) Clone a new repo cmpe273-lab1
3)Add requirements.txt file 
  "Requirements files" are files containing a list of items to be installed using pip install.Requirements files are used to force pip to properly resolve dependencies.
4)Add app.py file
  This file is created to help the user include any application configuration for the app.
5) Add Dockerfile
  Docker can build images automatically by reading the instructions from a Dockerfile, a text file that contains all the commands, in order, needed to build a given image. Dockerfiles adhere to a specific format and use a specific set of instructions.
6)Do a docker build
7)Run the Docker container using the image you created.
8)Lookup IP of the Lab1-flask-app container.
9)Run http://{IP_FROM_STEP_9}:5000/ from step 8
  
