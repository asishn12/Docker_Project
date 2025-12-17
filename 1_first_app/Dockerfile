# Pull base image for Python
FROM python:3.8-slim

# Set working directory in the image.
# app is the directory inside the image which will hold our application code.
WORKDIR /app

# Copy the current directory contents at /app in the image
COPY . /app  

# Command to run the application
# This will run app.py using python interpreter when the container starts.
CMD ["python", "app.py"]

# To build the Docker image, use the command:
# docker build -t first_app_image .. " . is the current directory where Dockerfile is present."

# To run the Docker container from the image, use the command:
# "docker run --name first_app_container first_app_image"