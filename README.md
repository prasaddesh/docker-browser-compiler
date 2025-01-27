# docker-browser-compiler
## An online code compiler using Docker

How to Run?
You can download and install Docker https://docs.docker.com/get-docker/⁠ Docker runs processes in isolated containers. A container is a process which runs on a host. The host may be local or remote.

### Docker Pull Command

`docker pull sidpro/compiler`

### Start a apache server instance

`docker run -p 8080:80 --name compiler -d sidpro/compiler`

Now you can check http://localhost:8080/⁠ in your browser.

### Stop Instance

`docker stop compiler`

### Remove Compiler

`docker rm compiler`
