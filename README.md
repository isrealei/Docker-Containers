# leaflite

### Project Description: Simple Website Deployment on a Virtual Machine(EC2 Instance) using Docker. 

This project involves deploying a simple static website to a Virtual machine (Amazon EC2 instance Droplets, Linode) using Docker. The website consists of HTML, CSS, and JavaScript files, and it is served using the Nginx web server. The process includes creating the website content or downloading already made website files, writing a Dockerfile to containerize the application, building the Docker image, and running the container on a virtual server.

**What you will learn from this project:**

- What is container?

- Why do we need containers?

- What is docker?

- How to create an image and run a container.

**Key Steps:**
1. **Create Website Content or Download the website content from tooplate:**
   - Develop the HTML, CSS, and JavaScript files to form the static website.
   - or Download the webiste file from [here](https://www.tooplate.com/).

2. **Dockerize the Application:**
   - Write a Dockerfile to use the official Nginx image and copy the website files into the appropriate directory for Nginx to serve.

3. **Build the Docker Image:**
   - Build the Docker image locally to package the website and Nginx server.

4. **Deploy to EC2 Instance:**
   - Launch an Amazon EC2 instance or any virtual machine of your choice.
   - Install Docker on the EC2 instance. For ubuntu install [here](https://docs.docker.com/engine/install/ubuntu/), for centOs install [here](https://docs.docker.com/engine/install/centos/).
   - Transfer the Docker image to the EC2 instance or build it directly on the instance.
   - Run the Docker container on the EC2 instance to serve the website.

5. **Access the Website:**
   - Configure security groups and firewall rules to allow HTTP traffic to the EC2 instance.
   - Access the website using the EC2 instance's public IP address or domain name.

**Benefits:**
- **Portability:** The website is containerized, making it easy to deploy across different environments.
- **Simplicity:** Using Docker and Nginx simplifies the process of setting up a web server.
- **Scalability:** The project can be easily scaled by running multiple containers or using container orchestration tools in the future.

This project demonstrates the use of Docker for packaging and deploying web applications and leverages AWS EC2 for hosting, providing a straightforward approach to web deployment without the complexity of Kubernetes.
