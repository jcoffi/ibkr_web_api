# Interactive Brokers Client Portal API - Docker Image

This Docker image provides a ready-to-use container for the Interactive Brokers Client Portal API, making it easy to deploy and run the API server.

## Features

- Based on Alpine Linux for a lightweight and secure environment.
- Simplified Dockerfile for easy customization.

## To Run
   
```shell
docker run -p 5000:5000 roozich/ibkr_web_api
```

## To Build

1. **Build the image:**

   ```shell
   docker build -t ibkr_web_api .
   ```
   
2. **Run the Docker container, mapping the desired port:**
   ```shell
   docker run -p 5000:5000 ibkr_web_api
   ```

3. **Open https://localhost:5000 to login and check the [API Documentation & Reference Guide](https://interactivebrokers.github.io/cpwebapi/) for usage.**
