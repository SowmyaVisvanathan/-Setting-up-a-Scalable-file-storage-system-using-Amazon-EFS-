### REG NUMBER: 212222110045
### NAME: Sowmya V

# SETTING UP A SCALABLE FILE STORAGE SYSTEM USING AMAZON ELASTIC FILE SYSTEM

## AIM
To  setting up a scalable file storage system using Amazon Elastic File System (EFS) for two EC2 instances in different availability zones. 

## PROBLEM STATEMENT
This experiment demonstrates how to configure Amazon EFS to provide a shared storage solution for two Linux EC2 instances across different availability zones, enabling easy data sharing. The aim is to ensure both instances can mount and access the EFS file system and validate data consistency across instances.

## ALGORITHM
 ### Steps 1: Create two EC2 instances in different availability zones.
 ### Steps 2: Set up a security group that allows necessary communication between the instances and EFS.
 ### Steps 3: Create an EFS file system and mount it to both EC2 instances.
 ### Steps 4: Ensure that the EC2 instances can access the file system and share data between them.

## COMMANDS
```
sudo su
yum install httpd -y
yum install -y amazon-efs-utils
mount -t efs -o tls fs-07000914021f4ad52:/ /var/www/html
cd /var/www/html
vi file1
cat file1
```

## OUTPUT

![image](https://github.com/user-attachments/assets/3e5e2f5f-59b0-4bf9-9dcb-4f87215e0b25)

![image](https://github.com/user-attachments/assets/f4f5aa6f-19a8-4aa4-8d2b-f5f3ec7e0b84)

![image](https://github.com/user-attachments/assets/9991f74e-5ed3-446f-a62f-6c73e134057b)

![image](https://github.com/user-attachments/assets/93a43aff-96a5-452a-be2f-26d0fefb14d7)

 
## RESULT
Thus, the setting up a scalable file storage system using Amazon Elastic File System (EFS) for two EC2 instances in different availability zones, enabling shared access to data is executed successfully.

  


