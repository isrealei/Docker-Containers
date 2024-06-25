# leaflite

### Project Description: Simple Website Deployment on EC2 Instance

This project involves deploying a simple static website to an Amazon EC2 instance using Docker. The website consists of HTML, CSS, and JavaScript files, and it is served using the Nginx web server. The process includes creating the website content, writing a Dockerfile to containerize the application, building the Docker image, and running the container on an EC2 instance.

**Key Steps:**
1. **Create Website Content:**
   - Develop the HTML, CSS, and JavaScript files to form the static website.

2. **Dockerize the Application:**
   - Write a Dockerfile to use the official Nginx image and copy the website files into the appropriate directory for Nginx to serve.

3. **Build the Docker Image:**
   - Build the Docker image locally to package the website and Nginx server.

4. **Deploy to EC2 Instance:**
   - Launch an Amazon EC2 instance.
   - Install Docker on the EC2 instance.
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
