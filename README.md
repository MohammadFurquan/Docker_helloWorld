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
