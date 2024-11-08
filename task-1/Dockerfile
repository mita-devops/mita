# Use official Nginx image as the base image
FROM nginx:latest

# Remove the default Nginx index page
RUN rm /usr/share/nginx/html/index.html

# Copy the custom index.html into the Nginx web directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 to be accessed outside the container
EXPOSE 80
