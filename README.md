# **_Docker_**
Introduction to Docker (Docker For Windows) 

Docker is a Container management service or shipping system for applications. Its useful for Developers to easily develop applications,
ship them into containers which than can run and be deployed on any platform. 
With Docker the beauty about it is that you can containers anywhere on any phyiscal or virtual machine or even cloud.
Docker is great for Developers who are always trying out new software. To run a MySQL or any Database server or just to setup some type of new service, Docker makes this quite Simple and save you hours. 
Docker has a lot of libarys to be imported so you can update your appliction by importing to the newest Library. 

## **_Requirements_**

Here are some of requirements you need to run docker on windows. 

- Windows 10 Pro or Education. 
- Hyper v is needed.
- Make sure no older version of docker is Installed.

## **_Installation Steps_**
1. Go into your control Panel and on the left where it says Turn windows Features on or Off select that link. 
2. You will see a lit of files with tick boxes beside them go down to Hyper-V and tick the box beside it.
3. Restart the Pc or laptop.
4. If you get an error after you restarted "Hyper-V is not running" Than you will you have reboot your pc and log into the Bios.
5. In the Bios you will need to enable The Hardware-assisted Virtualization and save then restart again.
6. After booting visit the [Docker](https://www.docker.com/community-edition#/windows) website and download docker for windows.
7. Click on the donload and accept the T&Cs and than docker should have started look at image below to see where to access docker. 

![](https://www.tutorialspoint.com/docker/images/kitematic.jpg)

8. To check or double check to see if Docker is running correctly open a PowerShell or Cmd and Type 
```
Docker version 
```
You should get this up Client and server settings 

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQf5WQPRN-U8L3p9eVtzd34JcYkg1TZRPXinq1g34QGKaML29C5VA)


## **_Containers_**
In Docker everything is based in Images its a combination on a file system and Parameters. Basically an Image is a snapshot of a container. Containers provide most of the isolation of a VM at a fraction of the computing power. 

#### 1. Here is basic commands in creating an image 
* [`docker create`](https://docs.docker.com/engine/reference/commandline/create) creates a container but does not start it.
* [`docker rename`](https://docs.docker.com/engine/reference/commandline/rename/) allows the container to be renamed.
* [`docker run`](https://docs.docker.com/engine/reference/commandline/run) creates and starts a container in one operation.
* [`docker rm`](https://docs.docker.com/engine/reference/commandline/rm) deletes a container.
* [`docker update`](https://docs.docker.com/engine/reference/commandline/update/) updates a container's resource limits.

#### 2. To Stop or start a Container use some of these....
* [`docker start`](https://docs.docker.com/engine/reference/commandline/start) starts a container so it is running.
* [`docker stop`](https://docs.docker.com/engine/reference/commandline/stop) stops a running container.

#### 3. Try and Run Hello world to test Docker try the command Below 
```
Docker run hello-world
```
you should get this message 
```
Hello from Docker!
This message shows that your installation appears to be working correctly.
```

## **__**
## **__**
## **__**


