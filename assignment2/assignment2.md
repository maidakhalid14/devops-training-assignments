# Assignment 2

- Create an Issue in this Git repo with Title `Assignment <NUMBER> - <FIRST_NAME-LAST_NAME>`
- Fork the Repository
- Protect your `main` branch so no one can push onto that branch even the administrators.
- Clone your forked Repository
- Create a Branch with name `Assignment <NUMBER> - <FIRST_NAME-LAST_NAME>`
- Create a file in this folder with your `<FIRST_NAME-LAST_NAME>.md`
- Answer the following questions in that file.

Q1) Share screenshot of the above Branch Protection of `main` branch


Q2) Explain Docker Containers vs VMs
A VM is a simulated computer system. It runs on virtualized hardware in a “sandboxed” environment on a computer or server. The term ‘virtualized hardware’ refers to VMs without dedicated hardware. Instead, these VMs use an allotted portion of the same hardware system. Sandboxed environments do not have direct access to their host system’s operating system (OS), files, or hardware. In effect, running a virtual machine involves installing an entire operating system that runs dual-booted via a hypervisor, in parallel with or instead of your native operating system
Vs
Docker containers may seem similar to virtual machines, but there are some key differences. Instead of abstracting the hardware, containers abstract the OS. But to better understand container technology, we must first take a look at the Docker ecosystem.

Q3) Explain Docker Architecture
Ans: 
Docker uses a client-server architecture. The Docker client talks to the Docker daemon, which does the heavy lifting of building, running, and distributing your Docker containers. The Docker client and daemon can run on the same system, or you can connect a Docker client to a remote Docker daemon. The Docker client and daemon communicate using a REST API, over UNIX sockets or a network interface. Another Docker client is Docker Compose, that lets you work with applications consisting of a set of containers


Q4) Write command to create an nginx container in detached mode with name `assignment-2` running on host port `9090` and container port `80` on a custom network named `assignment-2`
Ans:
Docker run –-assinment2 mynginx1 –p 9090:80 –d nginx

Q5) Write command to see logs of the above container
Ans: docker logs “assignment2”


Q6) Write commands to Exec into the container and cat the output of the default nginx file at /usr/share/nginx/html/index.html

Ans: 
  docker exec “assinment2” cat /usr/share/nginx/html.index.html

- Create a PR from this branch to your `main` branch
- Now create a PR from your `main` branch to the parent's(kahootali/devops-training-assignment) repo `main` branch
- Handle any comments on the review
- Get this PR merged into the parent repo
