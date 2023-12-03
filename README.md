Assignment 1 : start nginx container , port forward to local ,check logs , go inside the container and stop the nginx container 

Assignment 2 : 
Given that you have instructions to run the go-app ( in prerequisite ) 
1. Try to create a docker image out of it with the base image of `golang:latest`
2. Run a container with that image and do a curl request and make sure you are able to see the output.
3. Tag the docker image with v1.
4. Run docker history, observe and understand the output.
5. Push the docker image to your docker hub. 

Assignment 3 : create multi stage build and run dockerfile for go application 
1. stage1:build
2. stage2:Run

Assignment 4 :

1. Create a volume, call it my_volume.
2. Create container and attach my_volume
3. change something in the volume folder, e.g: add a file with some content.
4. create a second container mounted with the same volume, Check if file exists?

Assignment 5 :

Run redis container using official image
1. Note down the redis container IP
2. Pull code from branch redis in go app
3. Build new image for go-app
4. Start go-app container with redis ip as REDIS_HOST env
Eg: docker run -e REDIS_HOST-172.17.0.6 go-app-redis:v1
5. Make sure app go app work by /vote endpoint

 




		
 
