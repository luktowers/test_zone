# Use the official Python base image with the desired version
FROM python:3.9

# Set the working directory inside the container
WORKDIR /workspace

# Copy the requirements.txt file into the container
COPY requirements.txt .

# Install the required Python packages
RUN pip install -r requirements.txt

# (Optional) Install additional system dependencies if needed
# For example, to install curl:
# RUN apt-get update && apt-get install -y curl

# (Optional) Set any environment variables you need
# ENV MY_ENV_VAR=your_value_here

# (Optional) Install additional tools and dependencies

# (Optional) Expose any necessary ports
# EXPOSE 8000

# (Optional) Start your application or any other required commands
# CMD ["python", "app.py"]
