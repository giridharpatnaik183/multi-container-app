# Use a base image suitable for your application (e.g., Node.js, etc.)
FROM node:14

# Set the working directory inside the container
WORKDIR /app

# Copy the JavaScript files into the container (assuming you have a script.js file in service2 directory)
COPY script.js /app/

# Install dependencies (if any)
RUN npm install

# Specify the command to run your application
CMD ["node", "script.js"]

