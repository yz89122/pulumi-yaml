
# Amazon EKS Cluster

This example deploys an ECS Cluster with a Fargate service, served behind an Application Load
Balancer.

## Deploying the App

To deploy your infrastructure, follow the below steps.

## Prerequisites

1. [Install Pulumi](https://www.pulumi.com/docs/get-started/install/)
1. [Configure Pulumi for AWS](https://www.pulumi.com/docs/intro/cloud-providers/aws/setup/)

## Deploying and running the program


1.  Install required plugins:

    ```bash
    $ pulumi plugin install resource awsx 1.0.0-beta.5
    ```

1.  Create a new stack:

    ```
    $ pulumi stack init dev
    ```

1.  Set the AWS region:

    ```
    $ pulumi config set aws:region us-east-2
    ```

1.  Run `pulumi up` to preview and deploy changes:

    ```
    $ pulumi up
    Previewing changes:
    ...

    Performing changes:
    ...
    Resources:
        + 28 created

    Duration: 10m0s
    ```
