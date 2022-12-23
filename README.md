# class

How to create EC2 instance and connect

![image](https://user-images.githubusercontent.com/76540706/209405065-89193300-063d-48d1-a42b-751532200a26.png)

 

Steps:


1: Go to AWS console. click on All services, Click on Compute -->  Click on EC2



2. Click on Launch instance. Choose an Amazon machine image (AMI), click next


3. select Ubuntu Server 16.04 LTS (HVM), SSD Volume Type - ami-0552e3455b9bc8d50

click next

4. choose an instance type as t2.small, 2GB memory. click next


5. Leave values to default in step 3 and step 4. click next

6. enter tag name in step 5. Click to add a Name tag. it can be something like 
JenkinsEC2. click next:configure Security Group



7. Click create new security group, give name as MyJenkinsSecurityGroup, add custom rule for 8080, 8090 , allow 0.0.0.0/0 as source IP


8. Click on Review and launch

9. Click on Launch

Click on Launch

10. Choose the existing key pair if you have one, otherwise create new one, give some name as mySep18EC2Key. Make sure you download the key. Please do not give any space or any character in naming the key.



10. Click on launch instance, Scroll down and click on view instances.
![image](https://user-images.githubusercontent.com/76540706/209404870-317c1b50-7e5c-40c1-8d09-bd1038c66a51.png)

![image](https://user-images.githubusercontent.com/76540706/209405011-07a6e3a8-03ad-4f31-ba54-734bca997b26.png)

Once instance is created. you can see it running..
