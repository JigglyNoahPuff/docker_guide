# Introduction to Docker

## What is Docker?

> Docker is to containers as Libraries are to books

Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. 

### What are containers?
Docker is to containers as Google is to Google Search

#### Short and Sweet Explanation
Docker **Containers** are self-contained packages of software.  They are created on top of **Images** which host the operating system and explain which packages the container is to have.  Docker containers are designed in such a way that the important information is small and flexible in these containers.  This saves us from having to install a huge, ugly virtual machine.

#### Longer and Better Explanation
'Containers sit on top of a physical server and its host OS—for example, Linux or Windows. Each container shares the host OS kernel and, usually, the binaries and libraries, too. Shared components are read-only. Containers are thus exceptionally “light”—they are only megabytes in size and take just seconds to start, versus gigabytes and minutes for a Virtual Machines.'

'Containers also reduce management overhead. Because they share a common operating system, only a single operating system needs care and feeding for bug fixes, patches, and so on. In short, containers are lighter weight and more portable than VMs.' [blog.netap.com](https://blog.netapp.com/blogs/containers-vs-vms/)

### Why Docker?
> Docker is to containers as GitHub is to repositories
> 
#### Short and Sweet Explanation
Docker Containers seperate the specialized programs from the overall operating system.  This seperation allows easy packaging and sending of new code to computers regardless of whether it is a Mac, PC, or even Linux.

#### Longer and Better Explanation
'Docker enables developers to easily pack, ship, and run any application as a lightweight, portable, self-sufficient container, which can run virtually anywhere. Containers gives you instant application portability.'    

Containers do this by enabling developers to isolate code into a single container. This makes it easier to modify and update the program. It also lends itself, as Docker points out, for enterprises to break up big development projects among multiple smaller Agile teams to automate the delivery of new software in containers.[zdnet.com](https://www.zdnet.com/article/what-is-docker-and-why-is-it-so-darn-popular/)

Docker brings several new things to the table that the earlier technologies didn't. The first is it's made containers easier and safer to deploy and use than previous approaches. In addition, because Docker's partnering with the other container powers, including Canonical, Google, Red Hat, and Parallels, on its key open-source component libcontainer, it's brought much-needed standardization to containers.

Since then Docker donated "its software container format and its runtime, as well as the associated specifications," to The Linux Foundation's Open Container Project. Specifically, "Docker has taken the entire contents of the libcontainer project, including nsinit, and all modifications needed to make it run independently of Docker, and donated it to this effort." [zdnet.com](https://www.zdnet.com/article/what-is-docker-and-why-is-it-so-darn-popular/)
