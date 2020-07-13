### Static Website on AWS S3 Using Jenksin Pipeline

#  Log in to the AWS management console, as a Root user Create a new user credentials

![Screenshot 1](https://user-images.githubusercontent.com/4149567/87359479-809a0880-c52d-11ea-9ab4-2d66f19472e1.jpg)

# Create a new group and attach the following policies: AmazonEC2FullAccess, AmazonVPCFullAccess,AmazonS3FullAccess



![Screenshot 2](https://user-images.githubusercontent.com/4149567/87360109-01a5cf80-c52f-11ea-90b6-2aa80b174af3.jpg)

# Create a new key pair for access to your instance(s). You will used to ssh and access an EC2 instance.
# Launch the EC2 t2.micro for the free tier, pick "Ubuntu 18.04 LTS amd64.Once launched, create a security group for the vm. In the left sidebar, under Network and Security, select "Security Groups.

# Add Rule: Custom TCP Rule, Protocol: TCP, Port Range 8080, Source 0.0.0.0/0 Then add the SSH rule: Protocol: SSH, Port range: 22, From source, use the dropdown and select "My IP." You will need to create a VPC or use the defult VPC. If you have deleted your defualt VPC then you will have to create one. It very simple.






