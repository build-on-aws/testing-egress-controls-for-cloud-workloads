# Egress Controls with AWS Network Firewall and Amazon Route 53 Resolver DNS Firewall 

This repository contains the CloudFormation template used in the AWS Workshop: [Egress Controls with AWS Network Firewall and Amazon Route 53 Resolver DNS Firewall ](https://catalog.us-east-1.prod.workshops.aws/workshops/503778b9-6dbb-4e0d-9920-e8dbae141f43).

## Workshop Link

For detailed instructions, please follow the workshop guide at:
[https://catalog.us-east-1.prod.workshops.aws/workshops/503778b9-6dbb-4e0d-9920-e8dbae141f43](https://catalog.us-east-1.prod.workshops.aws/workshops/503778b9-6dbb-4e0d-9920-e8dbae141f43)

## AWS Hosted Events

It's recommended to run through AWS workshops at AWS hosted events, like [Activation Days](https://aws-experience.com/amer/smb/events/series/activation-days), where AWS provides temporary accounts with workshop resources.

This workshop has been published open source mainly to allow the CloudFormation template and egress-check.sh test script to be referencable.

## Deployment Instructions

The workshop environment can be deployed using a single CloudFormation stack (`Egress-Controls-Tutorial.yaml`) to deploy the workshop resources.

### Deployment Steps

1. Clone this repository
2. Navigate to the AWS CloudFormation console
3. Choose "Create stack" > "With new resources (standard)"
4. Upload the `Egress-Controls-Tutorial.yaml` file
5. Follow the prompts to create the stack (no parameter changes required)
6. Wait for the stack creation to complete (approximately 10-20 minutes)

## Cleanup

To delete all resources created by this workshop:
1. Navigate to the CloudFormation console
2. Select the main `Egress-Controls-Tutorial.yaml` stack
3. Choose "Delete"
