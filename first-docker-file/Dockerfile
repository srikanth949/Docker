FROM ubuntu:latest
WORKDIR /app
COPY . /app
RUN apt-get update && apt-get install -y python3 python3-pip
ENV NAME World
CMD ["python3","app.py"]


# # Use a lightweight Python image
# FROM python:3.12-slim

# # Set the working directory
# WORKDIR /app

# # Copy only requirements first for caching
# COPY requirements.txt .

# # Install Python dependencies
# RUN pip install --no-cache-dir -r requirements.txt

# # Copy the rest of the app
# COPY . .

# # Set environment variables (optional)
# ENV NAME World

# # Default command
# CMD ["python3", "app.py"]
