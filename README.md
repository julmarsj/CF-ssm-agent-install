EC2 Instance deployment and install of Systems Manager Agent (to manage instances at scale) via CloudFormation

Basic Info

At the time this document was written; SSM Agent is preinstalled on AMIs provided by AWS for the following operating systems (OSs):
Amazon Linux Base AMIs dated 2017.09 and later
Amazon Linux 2
Amazon Linux 2 ECS-Optimized Base AMIs
Amazon EKS-Optimized Amazon Linux AMIs
macOS 10.14.x (Mojave), 10.15.x (Catalina), and 11.x (Big Sur)
SUSE Linux Enterprise Server (SLES) 12 and 15
Ubuntu Server 16.04, 18.04, and 20.04
Windows Server 2008-2012 R2 AMIs published in November 2016 or later
Windows Server 2016, 2019, and 2022


You must manually install SSM Agent on Amazon EC2 instances created from other Linux AMIs.

https://catalog.workshops.aws/cfn101/en-US/basics/operations/session-manager#how-session-manager-works


Before you Begin

You must make note of the AMI/Instance ID of the instance that you wish to use, this is because cloudformation does not have the capability to list the AMI IDs.  
