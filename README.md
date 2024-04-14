# Interview-questions-outside
1) Have you worked on Linux?
- **what are the linux flavors?**
  - Ubuntu
  - Fedora
  - Debian
  - CentOS
  - Kali Linux
- **what is process management?**
   - Process creation : The OS create a new process when a program starts
   - Process shudule : The OS decides which process use CPU and when
   - Process termination: The OS ends the process when an error
   - Process Synchronization : Processes coordinates with their activities to aviod conficts
   - Inter-process communication : Processes share the data using IPC machanisam
- **How to create a User? and How to give permissions to the user.**
   - creating user using `sudo useradd username` command
   - Giving permission to user by using `sudo usermod -aG groupname username`
- **How do add a user to an Existing Group In Linux?**
   - `sudo usermod -aG groupname username`
- **How to Change the owner permissions of the User or the file?**
   - `sudo chmod username:groupname filename`
   - username: The name of the user that you want to see as owner
   - group name: The name of the group
-  **How to check the disk space in Linux?**
  - `df -h`
- **How to check memory in Linux?**
  -`free -h`
10) what does the top command Display?
11) what is the use of lsblk command in Linux?
12) How to do Disk partition in Ubuntu?
13) where is fstab in Linux?
14) what is the linux boot process?
15) what is a linux filesystem? and what is /etc and /bin?
16) what are Crontab and Cronjob?
17) what is virtualization?
18) what is SElinux?
19) How DNS works?
20) what is Apache?
21) What is PHPAdmin?
22) Do you know about firewalls?
23) what is an SSL certificate? How we can create the SSL certificate and where we will do the configurations in apache for the SSL certificate?
24) which is better apache or Nginx? for the higher load which webserver is best?
25) what is the path of apache configuration files?
26) what is Cloud Computing?
27) what is AWS?
28) what is EC2?
29) How we can configure the EC2 instance?
30) What is AMI?
31) How we can choose which instance type is required?
32) From where can we enable termination protection in EC2?
33) Suppose we have to install Ubuntu then where do we have to define OS while launching the EC2 instance?
34) what is .pem?
35) if we stop the ec2 instance then is the Private IP will change? or Not?
36) Can you explain about inbound rules of the default security group?
37) what is the Use of public and private IP?
38) what is a Security Group?
39) security Group is stateful How?
40) what is VPC?
41) what is CIDR?
42) what is Subnetting?
43) what is an internet gateway?
44) what is Nat and why do we use nat gateway?
45) what is Elastic IP?
46) Tell me about VPC peering.
47) what is S3?
48) what is Cloudtrail?
49) what is Cloudfront?
50) what is blue/green deployment?
51) what is Cloudformation and terraform?
52) what is Elastic beanstalk?
53) what is RDS? Is there a need to worry about backups?
54) what is Autoscaling and How many types of autoscaling policies?
55) what is Loadbalancer?
56) What is the difference between ALB and ELB?
57) what is PAAS?
58) Suppose you are working in a new company and you don’t know how to work on new projects for the new company then which approach you will follow?
59) what is ACM?
60) what is shell scripting? How do we use the script for Automation?
61) what is MySQL? How many ways we can use to take backup?
62) How many types of Jenkins plugins are there and what are their uses?
63) What is the command in docker container to delete all images which is not referenced by any other containers?
64) In GIT how can we move files/folders from one repository to another repository?
65) what is headless service in k8s and why we need to use ?
66) What are the default permissions assigned to a file in Linux upon creation?
67) what is the difference between bugs and vulnerabilities ?
68) What are the stages in your pipneline?
69) 1) diff between the top and htop
2) du -h and df -h
3) different storage types in aws and its use cases,how do you automate it using python
4) storage types vs storage classes
5) writing the single stage and multi stage dockerfiles
6) AWS cloud setup in the current project and which services we handle on daily basis ?
7) Which automated appraoch do you incorporate for cost optimization on daily basis in aws ?
8) diff between the ENTRYPOINT and CMD ?
1) How you can manage Kubernetes upgrade with Zero downtime!

2) How do you handle patches to production fleet of instances ( of course zero downtime )

3) How you manage micro services and what will be the branching strategies to manage code for the same ?

4) A instance not getting traffic , here is the temp AWS account, pls find the root cause via console ( or cli if you want to )

5) Here is the terraform code facing some issues , find why this error coming and fix it ( similar using CloudFormation if that’s in JD)

6) Here is one Kubernetes manifest file, for some reason the deployment having issues and changes not getting deployed to the deployment , find the issue and fix it!
7) how big jenkins server in your organisation?
8) Few Devops Questions and answers for freshers 💫
Q What is AWS DevOps?
Expects a basic understanding of the integration of AWS services with DevOps practices.

Q Can you name some core AWS services used in DevOps and their primary purposes?
Expects knowledge of services like AWS CodeCommit, CodeBuild, CodeDeploy, CodePipeline, CloudFormation, etc.

Q What is the significance of Infrastructure as Code (IaC) in AWS DevOps?
Aims to assess understanding of IaC concepts, with examples like AWS CloudFormation or Terraform.


Q Describe a project where you implemented CI/CD pipelines using AWS. Which services did you use and why?
Looks for hands-on experience in building and managing CI/CD pipelines using AWS services.

Q How have you used AWS monitoring and logging services in your past projects?
Expects examples of using services like CloudWatch, CloudTrail, or third-party tools.

Q Share an experience where you had to troubleshoot a deployment issue in AWS. How did you resolve it?
Seeks to understand problem-solving skills and familiarity with AWS deployment models and troubleshooting methods.

Q If you have to deploy a new application rapidly across multiple AWS regions, how would you approach it?
Tests knowledge of AWS global infrastructure and strategies for multi-region deployments.

Q How would you ensure security and compliance in your AWS DevOps processes?
Aims to assess understanding of AWS security best practices and tools (like IAM, Security Groups, NACLs, AWS Config, etc.).

Q Imagine you need to scale an application in AWS during peak times. What services and strategies would you use?
Expects knowledge of Auto Scaling, Elastic Load Balancing, and possibly serverless services.
git merge vs rebase and

git revert vs reset
1. Brief introduction about myself.
2. which CI/CD you worked most.
3. Can you explain your project with jenkins workflow
4. what is Jenkins file
5. What is slave in Jenkins. How to configure in jenkins?
6. Which server you use for hosting the your java application?
7. command to check the status of pods?
8. Did you create cluster of your own in your organization?
9. How many clusters are managed in your organization?
10. If cluster goes down how to troubleshoot it?
11. Command to check the logs in kubernetes
12. How to download the logs to your local
13. What is taint and tolerance
14. What is stateful and stateless
15. How to see service is available
16. type of services.What used in your organization
17. How to create certificates in AWS
18. If cluster goes down how to troubleshoot
19. How to move a folder from linux server to other linux server
20. 1.How do you connect from one server to another server.
2. What does happen in the back ground if we type DNS name ?
3. How does Load balancer works
4.What is the command to see all the processes
5. What is the background process of DB replication and why do we need to do that?
6.how do you check if a specific server is down ?
7. How do you know if any configuration change happens to a server in a group of 20 servers .If it is down how can you check it .
8. How do you create the automatic backup of the files with the instance ?
9. Kubernetes deployment process?
10. Application is down in Linux , how will you check that
11.How do you know if there are customers having issue to the specific location ?
