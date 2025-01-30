# Use the official Nginx image from the Docker Hub
FROM ubuntu:latest
 
 
RUN apt-get update && apt-get install -y nginx
 
# Copy the Nginx configuration file to the container
 
copy index.html /var/www/html/index.html
 
 
# Expose port 80
EXPOSE 80
 
# Start Nginx when the container has provisioned
CMD ["nginx", "-g", "daemon off;"]