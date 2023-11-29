Assignment 1 : start nginx container , port forward to local ,check logs , go inside the container and stop the nginx container 
  1.docker pull nginx  # pull nginx docker image from docker hub  
  2.docker run -it -p 1234:80 nginx bash # run nginx container interactive mode , open bash in container and port forward from 1234 to 80
  #enter control+D to come out from container 
  3.docker stop container_id #stop the container
