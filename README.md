
[![CircleCI](https://circleci.com/gh/Elkharbash/Udapeople.svg?style=svg)](https://app.circleci.com/pipelines/github/Elkharbash/Udapeople)

# Udapeople

The project is designed to showcase my skills and knowledge in the area of DevOps. The project is built using modern DevOps tools and practices to deploy and manage a Node js application in a production environment.

- [Screenshots](https://github.com/Elkharbash/Udapeople/tree/master/Screenshots)


![Logo](https://github.com/Elkharbash/Udapeople/raw/master/udapeople.png)


## Authors

- [Nabel Elkharbash](https://github.com/Elkharbash)


## Features

- Continuous Integration and Continuous Deployment (CI/CD) pipeline using CircleCI
- Automated deployment to AWS
- Infrastructure as code using AWS CloudFormation
- Confgiuration management using Ansible
- Application monitoring using AWS CloudWatch, Proemtheus and Visualization through Grafana
- Security best practices implemented (e.g., secure environment variables, secure communication over HTTPS)


## Installation

To install and deploy Udapeople project, follow these steps:

1. Clone the repository from GitHub:

```bash
git clone https://github.com/Elkharbash/Udapeople
cd Udapeople
```

2. Create a PostgreSQL database and set the database URI in the config.py file.

3. Set up  CircleCI and configure the necessary environment variables.

4. Push the changes to the GitHub repository, and CircleCI will automatically build and deploy the application to AWS.
```bash
git commit -m "testing the CICD pipeline"
```

5. check your CircleCI dashboard and the application should be under building process.
