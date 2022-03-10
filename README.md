# containerd_guide

This is a guide for containerd ctr a.k.a your typical docker client. 
If you are a developer working on images, then ctr you would normally use to pull down images, run containers and delete containers. 
You can pull images from docker hub.


Getting the release for your target platform. 
https://github.com/containerd/containerd/releases/tag/v1.4.0



To pull image 
ctr image pull mcr.microsoft.com/windows/servercore/iis:windowsservercore-ltsc2022

To run a container with the image called 'hello-world:nanoserver-ltsc2022' - a window image by the way. 

ctr container run docker pull hello-world:nanoserver-ltsc2022 hello --rm

ctr container delete hello - 


