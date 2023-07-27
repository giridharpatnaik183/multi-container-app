# Use a base image suitable for your application (e.g., Python, Nginx, etc.)
FROM python:3.9

# Set the working directory inside the container
WORKDIR /app

# Copy the HTML files into the container (assuming you have an index.html file in service1 directory)
COPY index.html /app/

# Install any additional dependencies if required by your application

# Specify the command to run the web server
CMD ["python", "-m", "http.server", "8000"]

