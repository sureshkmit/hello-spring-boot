# Hello App

A Spring Boot application containerized with Docker.

## Deployment to Render.com

1. Push this repository to GitHub
2. Go to render.com and create a new "Web Service"
3. Connect your GitHub repository
4. Select "Docker" as the environment
5. Configure the following:
   - Environment: Docker
   - Branch: main (or your preferred branch)
   - Root Directory: ./
   - No need to modify the Dockerfile path as it's in the root directory

The application will be automatically built and deployed using the Dockerfile.
