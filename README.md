Assignment 1 : start nginx container , port forward to local ,check logs , go inside the container and stop the nginx container 
  1.docker pull nginx  # pull nginx docker image from docker hub  
  2.docker run -it -p 1234:80 nginx bash # run nginx container interactive mode , open bash in container and port forward from 1234 to 80
  #enter control+D to come out from container 
  3.docker stop container_id #stop the container


Assignment 2 : 
	Given that you have instructions to run the go-app ( in prerequisite ) 
	1.	Try to create a docker image out of it with the base image of `golang:latest`
	2.	Run a container with that image and do a curl request and make sure you are able to see the output. 
	3.	Tag the docker image with v1. 
	4.	Run docker history, observe and understand the output. 
	5.	Push the docker image to your docker hub. 
 Assignment 3 : create multi stage build and run dockerfile for go application 
 			a.stage1:build
		  b.stage2:Run 
		Not completed
 Assignment 4 :
 1.Create a volume, call it my_volume.
 2.Create container and attach my_volume
 3.change something in the volume folder, e.g: add a file with some content.
 4.create a second container mounted with the same volume, Check if file exists?




		
 
