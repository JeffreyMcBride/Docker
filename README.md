# Docker Commands

Command 			| Switch 	| Definition
------------ 			| ------------- | -------------
`docker --version` 		| 		| Display version info 
`docker version` 		| 		| Display detailed version info of Docker client and server
`docker images` 		| 		| Display images in local Docker image registry
`docker ps`	 		| 		| Display running Docker containers
`docker run <image_name>` 	| 		| Locates, downloads if necessary, and runs a Docker image 
| `-d`						| Detached mode, runs Docker container in background
| `-p localPort:containerPort`			| Maps local machine port # to Docker container port 



Locates, downloads if necessary, and runs a Docker image  
`docker run <image_name>`  
:   Definition of first term Detached mode, runs Docker container in background  
    `-d`  
    Maps local machine port # to Docker container port #  
    `-p localPort:containerPort`

`docker stop <containerId>`				Stops a running Docker container with containerID
`docker build <path / url>`				Creates Docker image from Dockerfile in path / url
`	-t <friendlyName>`					Gives image a friendly name
`docker login`						Login to a Docker repository
`docker tag <imageName[:tag]> <iamgeName[:tag]>`	Tag a Docker image
`docker push <imageName[:tag]>`

