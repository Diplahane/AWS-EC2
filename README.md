# Deploying a Linux EC2 Instance and Connecting via SSH

-In this project, the goal is to launch an EC2 (Elastic Compute Cloud) Linux instance on Amazon Web Services (AWS) and establish a secure connection to it using the command-line interface (CLI) and SSH (Secure Shell) protocol.

# Step 1:

-Sign in to the "AWS Management Console".

![Screenshot_20230621_204606](https://github.com/Diplahane/AWS-EC2/assets/129828021/0d2e5452-d5f3-439d-94c6-12f49ef466c0)

# Step 2:

-Sign in to the AWS Management Console and navigate to the EC2 service

![Screenshot_20230621_204713](https://github.com/Diplahane/AWS-EC2/assets/129828021/181ebf3f-a651-4d45-b4e0-a7d5ab5aa82f)

# step 3:

-From the EC2 Dashboard go and select Launch instance.

![Screenshot_20230621_204745](https://github.com/Diplahane/AWS-EC2/assets/129828021/6c9a9bc8-b913-4661-9e41-5187d34fcb4e)


# Step 4:

-Name Your Instance, Choose an Amazon Machine Image (AMI) for the Linux server. You can choose from various Linux distributions available.

![Screenshot_20230621_204958](https://github.com/Diplahane/AWS-EC2/assets/129828021/8987fcbe-9603-467e-8fdc-1e60a94567ca)


# Step 5:

-Select the instance type that suits your requirements. Consider the CPU, memory, storage, and network capacity you need.

![Screenshot_20230621_205115](https://github.com/Diplahane/AWS-EC2/assets/129828021/a5c599bc-dfbe-4ad9-b4e3-955df210364f)

# Step 6:

-In Key pair select Create new key pair. Give (uniqe) Name to your key pair. This key pair will be used to securely connect to the instance via SSH.(make sure to download and securely store the private key file (.pem) in a safe location.)

![Screenshot_20230621_205205](https://github.com/Diplahane/AWS-EC2/assets/129828021/1a120c7c-2263-43ca-a09f-e87b0b0b3c13)

-Here is your downloaded Key pair file.

![Screenshot_20230621_211631](https://github.com/Diplahane/AWS-EC2/assets/129828021/b27a8489-22be-49d3-9037-50d7098a957c)


# Step 7:

-Configure Network setting including subnet, security group, etc. If you're not sure, you can use the default settings.(Allow SSH (port 22) access. By default, incoming SSH traffic is blocked for security reasons.)

![Screenshot_20230621_205453](https://github.com/Diplahane/AWS-EC2/assets/129828021/7fc39f3d-b3d1-48b3-aff4-8f06dd3f0d7f)


# Step 8:

-Configure the storage options for your instance. You can specify the size of the root volume and add any additional volumes if needed. Review all the configuration details you've set for the instance. If everything looks good, click on "Launch" to start the instance. 

![Screenshot_20230621_205630](https://github.com/Diplahane/AWS-EC2/assets/129828021/d502ea6b-605a-4c1a-9301-9e278dbb47e9)

-Successfully initiated lounch of "Instance"

![Screenshot_20230621_205737](https://github.com/Diplahane/AWS-EC2/assets/129828021/681b67f9-1679-448c-b6fc-ec6ced22883f)


# Step 9:

-Once the instance is running, you can connect to it using the CLI. Open your terminal or command prompt and navigate to the directory where your key pair file is stored.

![Screenshot_20230621_215500](https://github.com/Diplahane/AWS-EC2/assets/129828021/ce3be9a5-2482-4f46-9942-6215c8abbd17)


# Step 10:

-Go to the Ec2 instance. At the bottom of the screen, you will see a section called "Connect". Click on the "Connect" button. In the connection dialog, you will see different options for connecting to your instance, such as EC2 Instance Connect, Session Manager, and SSH. Select the "SSH client" tab. Here, you will find the SSH command that you can copy and paste into your CLI. and then press Enter to connect to your EC2 instance.

![Screenshot_20230621_211839](https://github.com/Diplahane/AWS-EC2/assets/129828021/8e5bd457-ba7a-494f-8540-7ed75662ab5a)

![Screenshot_20230621_211931](https://github.com/Diplahane/AWS-EC2/assets/129828021/6ac4c1da-e2f9-481a-a7bd-d39cafcac148)

![Screenshot_20230621_211947](https://github.com/Diplahane/AWS-EC2/assets/129828021/61299091-dca7-4649-b515-67bad1c80edf)

# That's it! You have successfully Deploying a Linux EC2 Instance and Connecting via SSH.
