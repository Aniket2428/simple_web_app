# Use the official Nginx image as the base image
FROM nginx:latest

# Copy the default Nginx configuration file
COPY default.conf /etc/nginx/conf.d/default.conf

# Expose port 80 to the outside world
EXPOSE 80

# Command to start Nginx
CMD ["nginx", "-g", "daemon off;"]
