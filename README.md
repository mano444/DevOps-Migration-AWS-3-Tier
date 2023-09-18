# DevOps Migration to AWS: 3-Tier Application


Welcome to the "DevOps Migration to AWS: 3-Tier Application" project repository. This project demonstrates the migration of a 3-tier application from a local development environment to the AWS cloud while implementing DevOps best practices for automation and efficiency.

## Project Overview

In this repository, we showcase the following key aspects:

### Migration to AWS

We transition a locally developed 3-tier web application to the Amazon Web Services (AWS) cloud infrastructure.

### Infrastructure as Code (IaC)

Leveraging Terraform, we define and provision AWS resources programmatically, promoting infrastructure consistency and scalability.

### Configuration Management

We use Ansible to automate server provisioning and application configuration, ensuring reproducibility and reducing manual intervention.

### Continuous Integration/Continuous Deployment (CI/CD)

Jenkins is employed to create automated pipelines for building, testing, and deploying the application, fostering rapid development cycles.

### Serverless Automation

AWS Lambda functions are introduced to automate routine tasks and optimize resource utilization.

### Monitoring and Security

We implement AWS CloudWatch for monitoring and logging, while adhering to security best practices to safeguard our application.

### Testing and Documentation

Automated testing is integrated into our CI/CD pipeline, and comprehensive documentation is provided to facilitate understanding and collaboration.

## Getting Started

Follow these steps to set up your development environment, deploy the application to AWS, and explore the automation workflows:

1. **Clone the Repository**: Clone this repository to your local machine.

    ```shell
    git clone https://github.com/mano444/DevOps-Migration-AWS-3-Tier.git
    ```

2. **Prerequisites**: Ensure you have the following prerequisites installed:

   - Terraform
   - Ansible
   - Jenkins
   - AWS CLI

3. **AWS Configuration**: Configure your AWS credentials and region:

    ```shell
    aws configure
    ```

4. **Terraform Setup**: Navigate to the Terraform directory and initialize the Terraform workspace:

    ```shell
    cd terraform/
    terraform init
    ```

5. **Ansible Playbook**: Execute the Ansible playbook for server configuration:

    ```shell
    cd ansible/
    ansible-playbook -i hosts main.yml
    ```

6. **Jenkins Pipeline**: Set up the Jenkins pipeline for automated deployment. Refer to `jenkins/` for configuration details.

7. **Lambda Functions**: Explore and deploy Lambda functions in the `lambda/` directory.

8. **Monitoring and Logs**: Set up AWS CloudWatch for monitoring and logging as per instructions in `monitoring/`.

9. **Testing**: Execute automated tests as part of the CI/CD pipeline. Refer to `tests/` for test scripts.

10. **Documentation**: Detailed documentation is available in the `docs/` directory. Refer to it for additional guidance and project details.

## Contributing

We invite you to join us on this journey of DevOps transformation and cloud migration. Contributions, feedback, and collaboration are highly encouraged.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

Feel free to explore our project and dive into the world of DevOps and AWS automation!



