# Flask + Express Jenkins CI/CD Deployment

## Project Overview
This project deploys a Flask backend and Express frontend on an AWS EC2 instance using Docker and Jenkins CI/CD pipeline.

## Technologies Used
- AWS EC2
- Jenkins
- Docker
- Flask (Python)
- Express (Node.js)
- GitHub

## Project Structure

Jenkins-Project/
├── Flask-Backend/
├── Express-Frontend/
├── Dockerfile
├── requirements.txt

## Deployment Steps

1. Created AWS EC2 instance
2. Installed Jenkins and Docker
3. Created Flask backend and Express frontend
4. Added Dockerfile
5. Configured Jenkins job
6. Jenkins pulls code from GitHub
7. Builds Docker image
8. Runs application container

## Docker Commands

Build Image:
docker build -t my-app .

Run Container:
docker run -d -p 5000:5000 --name my-container my-app

## Jenkins Pipeline

Jenkins automatically builds and deploys application after code update.

## Output

Application successfully deployed on EC2.

Backend:
http://EC2_PUBLIC_IP:5000

## Author
Shakti Kumar Behera
