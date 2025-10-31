# Use official Python base image
FROM python:3.9-bullseye


# Set working directory inside container
WORKDIR /app

# Copy local files into container
COPY . /app

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000 for the Flask app
EXPOSE 5000

# Command to run the application
CMD ["python", "app.py"]
