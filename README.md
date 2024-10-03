# Flask Docker App

This is a simple Flask application running inside a Docker container.

## Setup

1. Build the Docker image:

   ```bash
   docker build -t flask-app .

# Run the Docker container

docker run -p 5000:5000 flask-app

# Access the app at http://localhost:5000
