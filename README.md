# gob-2015
GridIron DevOps Hackathon

## 1. Build the Docker image
To build the Docker image, run the following command in the same directory as `Dockerfile`: 

`docker build -t loginapp .` 

Replace '`loginapp`' with whatever you want to name the image if you wish.

## 2. Run the Node.js app
First get the Docker image ID: 

`docker images`

Next run the Docker container processes:

`docker run -t -i <IMAGE ID>`

## 3. Use the app
First get the IP address of the Docker host:

`docker-machine ls`

Next, navigate to `<host IP>:49160` in your browser.
