### Demo Project:

Automate Node.js application Deployment via Ansible

### Technologies used:

Ansible, Node.js, AWS EC2 Instance, Linux

### Project Description:

1- Create EC2 Instance Server on AWS.

2- Write a hosts that includes the inventory lists and credentials

3- Write Ansible Playbook that installs necessary technologies, and deploys a NodeJS application with ec2 user

### Instruction

###### Step 1 Create a ec2 instance server in aws

1- Create a ec2 instance server in aws with port 22 open for ssh
![iamge](images/Screenshot%202023-04-20%20at%2011.08.09%20am.png)

###### Step 2 Write a hosts that includes the inventory lists and credentials

###### Step 3 Write Ansible Playbook

1-update yum and install nodejs and nvm via root user

2-install package.json and start node application via ec2-user

3-output the running process to ensure the application is running successfully

###### Step 4 Execute the ansible playbook

```
ansible-playbook -i hosts node_app.yaml
```

# The output of execution

![image](images/Screenshot%202023-04-20%20at%2010.23.30%20am.png)
