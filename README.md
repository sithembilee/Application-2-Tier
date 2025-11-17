**Table of Contents**

1. Project Overview
2. Architecture Flow
3. Steps
   - Create an AWS EC2 instance
   - Install dependencies and setuo
   - Configure GitHub Repository
     - Create Docker File
     - Create docker-compose.yml File
4. Jenkins Pipeline Creation and Execution
5. Conclusion
6. Infrastructure Diagram and Integration
7. WorkFlow Diagram

=====================================

**1. Project Overview**
This guide walks through the process of deploying a two-tier web application built with Flask and MySQL on an AWS EC2 instance.
The application is fully containerized using Docker and Docker Compose for easy setup and portability.
To streamline deployments, we set up a CI/CD pipeline with Jenkins, so every time new code is pushed to the GitHub repository, the build and deployment happen automatically.

=====================================

**2. Architecture Diagram**
