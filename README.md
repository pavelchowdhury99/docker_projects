# Docker Fundamentals Beginners and Project Ideas

## Need for Docker
1. Problem of environment separation for applications.
2. Problem of resource sharing.
3. Problem of portability.
4. Problem of easy scalability.
5. Problem of doing all this in a secured manner.

## Evolution of solutions
1. Virtual Machines or VM
2. Docker
   ![Docker vs VMs](https://miro.medium.com/max/1024/1*66cp6uoqv-q2clolRgSRJg.png)
3. Advantages of Docker
   1. All container share same kernel - thus storages is saved.
   2. Container boot time is less.
   3. Support for version control.
   4. Multiple container can start from single docker image and communicate.
   5. Images can be built on top of another.
   
## Installing docker to yours system.
1. [Install docker](https://docs.docker.com/get-docker/).
2. Initiate docker.
3. Check if it's working by ```docker version``` or ```docker-compose version```.

## Docker Image vs Container
1. Images are blueprint and container their instance.
2. To create image, we need to write instruction in ```Dockerfile``` and to create the container run the image.

## Docker Compose vs Dockerfile
