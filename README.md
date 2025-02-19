# CloudFormation Templates

## Overview

AWS CloudFormation is a service that helps you model and set up your Amazon Web Services resources so that you can spend less time managing those resources and more time focusing on your applications. With CloudFormation, you can use a template to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion.


## Features

- **Infrastructure as Code**: Define your infrastructure using code, making it easy to version and manage.
- **Automated Resource Management**: Automatically create, update, and delete resources as needed.
- **Declarative Syntax**: Use JSON or YAML to describe your resources and their configurations.
- **Stack Management**: Group related resources into stacks for easier management.


## Getting Started

### Prerequisites

- An AWS account
- Basic knowledge of AWS services
- Familiarity with JSON or YAML


### Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/cloudformation-templates.git
   ```

2. **Navigate to the Templates Directory**:
    ```bash
    cd cloudformation-templates
    ```

3. **Deploy a Template: Use the AWS CLI or AWS Management Console to deploy a CloudFormation template. For example:**
    ```bash
    aws cloudformation create-stack --stack-name my-stack --template-body file://template.yaml
    ```

## This repository consists of labs wrt templates from basic's to advanced.

## Acknowledgements

I would like to extend our special thanks to **STACKSIMPLIFY** for their invaluable references , resources which help me understand the concept not just theoretically but more practically which made this repository possible. 