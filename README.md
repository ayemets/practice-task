# Practice task for SRE/DevOps internship

Paul, the CTO in your company, is very interested in containerisation technology. You were tasked to get your hands-on with Docker. So in this task, you need to set up a custom application in the container.

Task

0. Warmup

To learn about docker, do the following simple tasks:
  Run nginx container locally with an exposed port. 
  
  Make sure that you can access the default nginx page on the exposed port.
  
  Run nginx container locally with exposed port and replace default index.html file with your own.
  
  Make sure that you can access your page on the exposed port.
  
  Build container dev-tools created from ubuntu image, and install git, make, build-essential packages.
  
  Upload previously created image dev-tools to dockerhub. Try to pull it from dockerhub.

1. Repository

Fork repository for task and clone forked repo.

2. Build docker image

You need to update Dockerfile that has nginx with php support, copy file index.php to the required folder, and make sure nginx and container set up so that after starting a container, you should see rendered php page in your browser by address http://localhost:8080/index.php.
Upload your docker image to DockerHub: Create a free account in DockerHub. Push your recently built docker image to dockerhub.

3. Make your work visible

Create Pull Request with changes on Dockerfile.

Additional task if you feel that it was too easy.

Instead of copying index.php to the container, find a way to edit this file locally and see your changes after refreshing the page.

Tips:

Docker allows you manipulating containers. Containers are more lightweight than VM, enabling you to run more applications on the same hardware.
