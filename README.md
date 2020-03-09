#Readme

Steps:

Create ECS Cluster

![Create ECS Cluster](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/1-Create%20ECS%20Cluster.JPG)

Select option

![Select option](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/2-ECS%20Select.JPG)

Configuration step 1

![Configuration step 1](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/3-Config.JPG)

Configuration step 2

![Configuration step 2](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/3-Config.JPG)

Configuration step 3

![Configuration step 3](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/4-config.png)

Configuration step 4

![Configuration step 4](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/5-config.JPG)

ECS Created

![ECS Created](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/6-ECS%20Created.JPG)

ECS Cluster with one node ready

![ECS Cluster with one node ready](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/7-ECS%20Cluster%20with%20one%20node%20ready.JPG)

ECS 

![ECS](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/8-ECS.JPG)

Configuration Details in the file

![Configuration Details in the file](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/17-Config%20details.JPG)

Task definition

![Task definition](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/19-Create%20task%20definition.JPG)

ECS Selection

![ECS Selection](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/2-ECS%20Select.JPG)



Verify Corresponding EC2 Instance

![Verify Corresponding EC2 Instance](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/9-Corresponding%20EC2%20Instance.JPG)

New Autoscaling group created in EC2 automatically

![New Autoscaling group created in EC2 automatically](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/10-New%20Autoscaling%20group%20created%20in%20EC2%20automatically.JPG)

Autoscaling group with EC2 instance configuration

![Autoscaling group with EC2 instance configuration](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/11-Autoscaling%20group%20with%20EC2%20instance%20configuration.png)

Launch configuration

![Launch configuration](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/12-Launch%20configuration.png)

User Data section in EC2 from Launch Configuration shows how EC2 is configured to register with ECS
![User Data section in EC2 from Launch Configuration shows how EC2 is configured to register with ECS](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/13-User%20Data%20section%20in%20EC2%20from%20Launch%20Configuration%20shows%20how%20EC2%20is%20configured%20to%20register%20with%20ECS.JPG)

Security group - I have added ssh inbound

![Security group - I have added ssh inbound](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/14-security%20group%20-%20I%20have%20added%20ssh%20inbound.JPG)

Check ssh is working

![Check ssh is working](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/15-ssh%20happens.JPG)

List Docker images

![List Docker images](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/16-listed%20docker%20images.JPG)

Host file config details

![Host file config details](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/17-Config%20details.JPG)

Create Task definition

![Create Task definition](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/19-Create%20task%20definition.JPG)

Task definition - config

![Task definition - config](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/20%20-%20Config.JPG)


CPU & Memory allocation for the container
![CPU & Memory allocation for the container](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/21%20-%20Config.JPG)

Enter container image details
![Enter container image details](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/22%20-%20Container.JPG)

Task definition created successfully

![tas definition created successfully](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/23%20-%20Task%20definition%20created.JPG)

Task definition status

![Task definition status](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/24%20-%20Task%20definition.JPG)

Fargate service configuration - here minimum healthy percent is kept as 0 for rolling update

![Fargate service configuration - here minimum healthy percent is kept as 0 for rolling update](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/25%20-%20Fargate%20service%20definition.JPG)

VPC & Subnet selection

![VPC & Subnet selection](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/26%20-%20Config.JPG)

Service created successfully

![Service created successfully](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/27%20-%20Service%20Created.JPG)

Service status

![Service status](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/28%20-%20Service%20created%20successfully.JPG)

Find the EC2 public ip address and run the app using the ip and port

Here argument passed as 10 and it returns square root of 10 i.e. 100

![Find the EC2 public ip address and run the app using the ip and port](https://github.com/banerjee82/aws-fargate-demo-with-python/blob/master/29%20-Run%20the%20app%20using%20public%20ip%20of%20EC2%20and%20it%20works.JPG)