# Use the official Nginx image as the base image
FROM nginx:1.25.3

# Copy your custom Nginx configuration file into the container
COPY index.html /usr/share/nginx/html

# Expose port 80 for incoming HTTP traffic
EXPOSE 80

# Start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
