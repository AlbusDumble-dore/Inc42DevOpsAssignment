
# Use an official WordPress image as the base image
FROM wordpress:latest

# Set the working directory inside the container
WORKDIR /var/www/html/wp-content/themes/my-theme

# Copy the theme files from the local machine to the container
COPY . .

# Expose port 80 to the outside world
EXPOSE 80
