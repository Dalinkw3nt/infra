A CloudFormation template with the following components
    * An Amazon Virtual Private Cloud
    * An internet gateway attached to the VPC
    * Security groups for accessing the VPC configured to allow SSH from anywhere
    * A private subnet within the VPC
    * An Amazon EC2 instance (a T3.micro) within the private subnet
