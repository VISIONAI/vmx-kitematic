
![visionai/vmx-kitematic](http://blog.vision.ai/images/visionai_kitematic.png)

A single bundle which includes vision.ai's computer vision server,
VMX, as a single Docker container.  This is intended to be installed
via Kitematic, a graphical user interface, for installation of Docker
containers directly from Docker Hub.

There is a description of the installation procedure in the following
blog.vision.ai blog post from March 16th, 2015.
[Dockerized Computer Vision for Mac via Kitematic](http://blog.vision.ai/vmx/2015/03/16/dockerized-computer-vision-for-mac-via-kitematic/)

### Installing with docker

The container is automatically built on Docker Hub under
[visionai/vmx-kitematic](https://registry.hub.docker.com/u/visionai/vmx-kitematic/). It
can pull down with the following command:
```
docker pull visionai/vmx-kitematic
```

### Manually building the container

I'm not sure why you'd want to do this, but if you want to build the
container from source on your own machine, issue the following command:
```
docker build .
```

### Credits

Created by the team at vision.ai
