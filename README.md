AWS Infrastructure Practice Project
This project is designed as a hands-on learning experience for deploying a web application on AWS infrastructure. The primary focus is understanding and implementing AWS services and a basic CI/CD pipeline using GitHub Actions.

Note: This project is for educational purposes and is not ready for production environments.

Architecture
The application employs a microservices architecture, leveraging the following AWS services:

EC2: Hosts the backend application, PostgreSQL database, and Redis instance, all containerized and managed with Docker Compose.

S3: Provides storage for the static frontend content.

CloudFront: Acts as a content delivery network, serving the static files from S3 with caching enabled for optimal loading times.
