# Interactive Brokers Client Portal API - Docker Image ( unofficial )

This Docker image provides a ready-to-use container for the Interactive Brokers Client Portal API, making it easy to deploy and run the API server.

## Features

- Based on Alpine Linux for a lightweight and secure environment.
- Simplified Dockerfile for easy customization.

## Usage

1. **Build the Docker image:**

   ```shell
   docker build -t ibkr-api .
   
2. **Run the Docker container, mapping the desired port:**
   ```shell
   docker run -d -p 5000:5000 ibkr-api

3. **Open https://localhost:5000 to login and check the [API Documentation & Reference Guide](https://interactivebrokers.github.io/cpwebapi/) for usage.**
