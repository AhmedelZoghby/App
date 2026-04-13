# Use a lightweight official Python image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Install the exact dependencies you used earlier
RUN pip install --no-cache-dir Flask flask-socketio

# Copy all the files from your current folder into the container
COPY . /app

# Tell Docker that the app listens on port 5000
EXPOSE 5000

# The command to start the app
CMD ["python", "app.py"]

