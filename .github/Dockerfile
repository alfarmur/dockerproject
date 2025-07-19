# Use a base Python image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the Python script and requirements file into the container
COPY ./app
# COPY requirements.txt .

# Install Python dependencies
RUN pip install --no-cache-dir -r requirements.txt
expose 5000
# Specify the command to run when the container starts
CMD ["python", "app.py"]
