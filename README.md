
![visionai/vmx-kitematic](http://blog.vision.ai/images/visionai_kitematic.png)

A single bundle which includes vision.ai's computer vision server,
VMX, as a single Docker container.  This is intended to be installed
via Kitematic, a graphical user interface, for installation of Docker
containers directly from Docker Hub.

![kitematic-image](http://blog.vision.ai/images/visionai_kitematic.png)

There is a description of the installation procedure in the following
blog.vision.ai blog post from March 16th, 2015. [Dockerized Computer
Vision](http://blog.vision.ai/vmx/2015/03/16/dockerized-computer-vision-for-mac-via-kitematic/)

### Installing with docker

The container is automatically built on Docker Hub under
[visionai/vmx-kitematic](https://registry.hub.docker.com/u/visionai/vmx-kitematic/). It
can be pulled down with the following command:
```
docker pull visionai/vmx-kitematic
```

### Manually building the container

If you want to build the container from source on your own machine,
issue the following command:

```
docker build .
```

### Credits

Created by the team at vision.ai
