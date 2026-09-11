# Laboratory 04 – Cloud-Native Engineer

## Mission Overview
This laboratory introduces the shift from traditional virtualization to containerization. Using KillerCoda, I learned how to pull, run, manage, and remove Docker containers by deploying an Nginx web server in just a few seconds.

## Objectives
- Differentiate between Virtual Machines (VMs) and Containers
- Access a Docker-enabled cloud environment using KillerCoda
- Execute fundamental Docker CLI commands
- Pull, run, manage, and terminate a containerized application (Nginx)
- Create professional technical documentation using Markdown
- Continue developing a well-organized GitHub Cloud Computing Portfolio

## Docker Commands Executed
- `docker --version`
- `docker info`
- `docker pull nginx`
- `docker run -d -p 8080:80 --name my-nginx nginx`
- `curl http://localhost:8080`
- `docker ps`
- `docker stop my-nginx`
- `docker ps -a`
- `docker rm my-nginx`

## Skills Learned
- Understanding the architectural differences between Virtual Machines and Containers
- Using the Docker CLI to manage the full container lifecycle
- Port mapping and verifying containerized web services
- Writing clear and organized technical documentation in Markdown
- Maintaining a professional GitHub portfolio structure

## Challenges Encountered
At first, I was a bit confused about which KillerCoda playground to use. I also needed some time to understand why we map port 8080 to port 80. Taking clear screenshots and organizing the files in the correct folders also took a little effort, but I was able to complete everything successfully.
