Creating an EC2 (Elastic Compute Cloud) server in AWS involves several steps. Here's a general outline of the process:

Sign in to the AWS Management Console: Log in to your AWS account.

Navigate to the EC2 Dashboard: You can find the EC2 service under the "Compute" section in the AWS Management Console.

Launch Instance: Click on the "Launch Instance" button to start the process of creating a new EC2 instance.

Choose an Amazon Machine Image (AMI): Select an AMI that suits your requirements. This is essentially the operating system and software stack that will be installed on your EC2 instance.

Choose an Instance Type: Select the instance type that meets your performance and resource requirements. Each instance type comes with a specific combination of CPU, memory, storage, and networking capacity.

Configure Instance: Configure additional settings such as network settings, storage options, security groups, and key pairs. Security groups act as firewalls for your instance, controlling inbound and outbound traffic. Key pairs are used for securely connecting to your instance via SSH (for Linux) or RDP (for Windows).

Review Instance Launch: Review your instance configuration to ensure everything is set up correctly.

Launch Instance: Once you're satisfied with the configuration, click the "Launch" button to create your EC2 instance.




![Capture1](https://github.com/jyothikaraj11/Git-Practice/assets/154610655/217ba354-d062-4178-a68c-7643dcb0c352)













Create or Select a Key Pair: If you haven't already created a key pair, AWS will prompt you to create one. This key pair is essential for securely accessing your instance.




![Capture3](https://github.com/jyothikaraj11/Git-Practice/assets/154610655/d65b8251-0017-4b0d-9f52-30412461bd42)








Accessing Your Instance: Once your instance is launched, you can connect to it using SSH (for Linux instances) or RDP (for Windows instances) using the key pair you selected or created.

Configure Your Instance: After connecting to your instance, you can configure it further by installing software, setting up applications, and managing users and permissions.

Terminate Your Instance: When you're done with your instance, remember to terminate it to avoid incurring unnecessary charges. You can do this from the EC2 Dashboard by selecting your instance and choosing "Instance State" > "Terminate". 




we can go to  browser and take jenkins repo

![Capture9](https://github.com/jyothikaraj11/Git-Practice/assets/154610655/cb5d3d0b-2398-4059-8c15-8620d5dd3eda)




We haveto paste That Jenkins Repo and keys Like below shown



![Capture 4](https://github.com/jyothikaraj11/Git-Practice/assets/154610655/c60dfeee-97df-418a-a4e6-ec8b317b73cc)


After completed repo installation  we haveto install Amazon epel pakeges and maily java11
 By using this command

 Amazon-linix-extras install epel,

 and java11 instalation
 Amazon-linux-extras install java -open jdk 11

 ![Capture8](https://github.com/jyothikaraj11/Git-Practice/assets/154610655/18dafc72-433c-495a-b13c-feeb05aeb773)

 After java instalation completed we have to install JENKINS by using YUM command

 yum install jenkins

 yum install git

 yum install maven

 after instalation completed all those tools in server we have to open jenkins in browser by using PORT NUMBER, and IP NUMBER.

 Thats it Jenkins Instalation completed.
 

 














