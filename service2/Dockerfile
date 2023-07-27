# Use the official MySQL base image
FROM mysql:latest

# Set the MySQL root password (change this to a secure password in production)
ENV MYSQL_ROOT_PASSWORD=root_password

# Copy any SQL initialization scripts to the appropriate directory
COPY script.js /app/
