# **Docker**
Docker is a platform that enables developers to create, deploy and run applications in a portable, isolated environment known as a container. The containerization feature of Docker provides a secure and efficient way to run multiple applications on a single host, as each container runs in its own isolated environment. This means that containers are lightweight, self-sufficient and include everything needed to run the application, eliminating the need to rely on the host's pre-installed dependencies. Additionally, Docker's containerization makes it easy to share and distribute applications, ensuring that they work consistently across different environments.

## **Experience**
 The task of installing and configuring Docker on my system was not only intellectually stimulating but also an incredibly enriching experience. The process of delving into the documentation and troubleshooting various challenges related to the use of Linux or Windows containers for building my applications, added an extra layer of excitement and engagement to the task. Despite encountering a few hiccups along the way, the experience has expanded my knowledge and proficiency in utilizing the Docker platform, making it all the more worthwhile.

## **Problem - 1:-**
The Docker Desktop application appears to be stuck in an infinite loop, continuously displaying the message *"Docker Desktop starting...".*

## **Problem - 2 :-**
*"error during connect: This error may indicate that the docker daemon is not running.: Post "http://%2F%2F.%2Fpipe%2Fdocker_engine/v1.24/build?buildargs=%7B%7D&cachefrom=%5B%5D&cgroupparent=&cpuperiod=0&cpuquota=0&cpusetcpus=&cpusetmems=&cpushares=0&dockerfile=Dockerfile&labels=%7B%7D&memory=0&memswap=0&networkmode=default&rm=1&shmsize=0&t=getting-started&target=&ulimits=null&version=1": open //./pipe/docker_engine: The system cannot find the file specified."*

After conducting thorough research and development, I was able to identify a specific command that effectively resolved the issue of the Docker Desktop being stuck in an infinite loop displaying the message "Docker Desktop starting...", enabling me to utilize the platform and its functionalities once again

## **Solution :-**
**Step 1** :- open cmd and Run as administrator<br>
**Step 2** :- write this cmd "cd "C:\Program Files\Docker\Docker"
./DockerCli.exe -SwitchDaemon"<br>
**Step 3** :- then do build and run according to the given documentation

## **Suggestion :-**
I believe that incorporating short, *instructional videos* for each step in the documentation would greatly benefit users experiencing similar issues. Based on my own experience and observation, it appears that many individuals are encountering the same problem and resorting to seeking assistance on forums such as StackOverflow. By including this information in the documentation and supplementing it with visual aids in the form of videos, the process of troubleshooting and resolving issues would be greatly streamlined for users. I also noticed that my friend also faced the same problem, which underlines the need for this change.
