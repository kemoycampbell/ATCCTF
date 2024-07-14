# Use the official Python slim image from the Docker Hub
FROM python:slim
# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Run the Python script when the container launches
CMD ["python", "app.py"]