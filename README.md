# Docker Commands

Display version info - 17.06.0-ce build 02c1d87  
`docker --version`

Display detailed version info of Docker client and server  
`docker version`

Display images in local Docker image registry  
`docker images`

Display running Docker containers  
`docker ps`

`docker run <image_name>`				Locates, downloads if necessary, and runs a Docker image
`	-d`							Detached mode, runs Docker container in background
`	-p localPort:containerPort`				Maps local machine port # to Docker container port #
`docker stop <containerId>`				Stops a running Docker container with containerID
`docker build <path / url>`				Creates Docker image from Dockerfile in path / url
`	-t <friendlyName>`					Gives image a friendly name
`docker login`						Login to a Docker repository
`docker tag <imageName[:tag]> <iamgeName[:tag]>`	Tag a Docker image
`docker push <imageName[:tag]>`

