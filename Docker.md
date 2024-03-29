# Docker

In this file, I will explain how Docker can improve productivity and competitiveness of a company.

Before Docker, companies were running applications on a single machine (virtual machine). This process was called virtualization. These virtual machines were bulky, performed poorly, and took long to boot. With this hardship, the idea of containerization was introduced. Containerization is another type of virtualization with applications running at the operating system level. Processing applications were faster and took a second to boot. Containerization brought Docker. Docker is a containerization platform that packages all of an application’s dependencies into a Docker container to be deployed. It ensures an application can work in any environment. 

Docker improves productivity and competitiveness of a company in three ways: size, startup, and integration. Size is defined as how much capacity is utilized. As compared to virtual machines, a Docker Container only allocates the amount of memory required to perform. A virtual machine is unable to re-allocate memory. By using a virtual machine, you lost the ability to setup up an additional virtual machine and risk spending extra money on purchasing more RAM. Whereas, a Docker Container increases productivity by allowing more containers to be created on unused RAM. Startup is time required to boot an application. When a virtual machine boots up, the operating system starts from scratch. It is time consuming and costly. Conversely, a Docker Container runs on the operating system (typically lightweight and faster). This saves boot time as applications need to be available faster for developers.  Lastly, integration is ability to integrate with other tools. A virtual machine allows for one running instance of applications like [Git](https://github.com/Shannon-NJIT/MiniProject1/commit/37ae6b308a6694bd9863ccb36cd23756ef7f5765). This can create problems for a company because it slows down productivity if an update needs to be installed on every virtual machine. However, a Docker Container can run many instances of a program. A program can run within one container or amongst multiple while still interacting with one another. The use of Docker clearly benefit developers as companies utilize a DevOps practice to sustain competitive advantage

![Docker](/images/images/docker.png)
*Source: https://www.nakivo.com/blog/docker-vs-kubernetes/*




