# Docker HelloWorld

This repository contains the Docker image "HelloWorld" which displays the message "Hello World" along with a stopwatch.

## Docker Hub Image

You can find the Docker image on Docker Hub [here](https://hub.docker.com/repository/docker/mdfurquan313/helloworld/general).

### Pulling the Docker Image

To pull the Docker image, run the following command:

```bash
docker pull mdfurquan313/helloworld
```

### Running the Docker Image
To run the Docker image, execute the following command:

```bash
docker run -dp 3000:80 mdfurquan313/helloworld
```

### Building and Running Locally
If you want to build and run the Docker image locally, follow these steps:


## Step 1: Clone the Repository
Using Git:

```bash
git clone https://github.com/MohammadFurquan/Docker_helloWorld.git
```
Or download the repository as a ZIP file and extract it.


## Step 2: Navigate to the Repository Folder
Open a terminal and navigate to the folder where the repository is located:

```bash
cd Docker_helloWorld/helloworld
```

## Step 3: Build the Docker Image
Run the following command to build the Docker image:

```bash
docker build -t <image_name> .
```

## Step 4: Verify the Docker Image
Check the built image using the following command:

```bash
docker image ls
```

## Step 5: Run the Docker Image
Run the following command to start the Docker image:

```bash
docker run -dp 3000:80 <image_name>
```


### Files in this Repository
- *`Dockerfile`* : Defines the Docker image.
- *`app.py`* : The application script.
- *`requirements.txt`* : Lists the Python dependencies for the application.





---






# Docker_helloWorld
Docker_first_image
I have created my first image of docker "HelloWorld" which shows message Hello World with StopWatch.
Here is link of my image of Docker Hub https://hub.docker.com/repository/docker/mdfurquan313/helloworld/general
You can use this image, run a command as "docker pull mdfurquan313/helloworld". To run the image you need to run a command as "docker run -dp 3000:80 <image_id?"



If you want to download dockerfile locally download this folder "helloworld" locally 
STEP:1
1. Using "Git"
2. Downloading Zip file of this repository

STEP:2
Open Terminal in the folder of repository which you have downloaded

STEP:3
Run the following command to build docker image
"docker build -t <image_name> ."

STEP:4
Now check the image by using the following command
"docker image ls"

STEP:5
Run the following command to run the image
"docker run -dp 3000:80 <image_id>"
