# Final-Project
# CI/CD Pipeline for Legacy Application

This project implements a CI/CD pipeline to convert a legacy development process to a DevOps process for a US healthcare company, Aetna. The objective is to implement iterative deployments, continuous innovation, and automated testing through the assistance of the strategy.

## Problem Statement

Aetna has a large IT structure and a 12-week release cycle, which is impacting their business. To gain true business value through faster feature releases, better service quality, and cost optimization, they want to adopt agility in their build and release process.

## Implementation Requirements

- Install and configure the Jenkins architecture on AWS instance
- Use the required plugins to run the build creation on a containerized platform
- Create and run the Docker image which will have the application artifacts
- Execute the automated tests on the created build
- Create your private repository and push the Docker image into the repository
- Expose the application on the respective ports so that the user can access the deployed application
- Remove container stack after completing the job

## Step-by-Step Process

1. Install and configure Jenkins on an AWS instance
2. Install necessary plugins for running Docker builds
3. Create a Jenkins pipeline to build and test the application
4. Create a Dockerfile to package the application in a Docker container
5. Build the Docker image and push it to a private repository
6. Deploy the Docker container to a server and expose the necessary ports
7. Test the application to ensure it is working as expected
8. Remove the Docker container and associated resources

## Contact

If you have any questions or concerns, please contact the project maintainer at devops@aetna.com.
