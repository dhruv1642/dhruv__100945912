# Use an official Python runtime as the base image
FROM python:3.9-slim

# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set the working directory
WORKDIR /app

# Copy the application code and template
COPY . /app

# Install Flask dependencies
RUN pip install flask

# Command to run the application
CMD ["python", "app.py"]