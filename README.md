This is a Simple a Java Applications
If you run it in a container you will get output on terminal

First You Need to Build Docker Image using Provided Dockerfile,
Use Following Command to build Docker image

docker build -t my-java-app .

To run Container, Use following command 

docker run -it --rm --name simple-java-app my-java-app
