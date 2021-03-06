# DevOps / SRE Interview Questions

## Linux
1) What is booting process in Linux
2) What is inode in Linux how to increase it
3) What is logical volume and how to create it
4) What is swap partition and how to create
5) Tell me about some commands in Linux
6) Ho to check the process pot and name(netstat –tulnp)
7) How to kill a process
8) What are ACLs and firewall and selinux
9) How to do the networking using the nmcli
10) How to manage the disk space ,RAM and memory
11) What is TOP command and how to fetch the data
12) What is load average in Linux systems and what does three components of load average defines
13) How to assign the process the required amount of resource allocation
14) What is nohup and &
15) User management, file management, log management
16) How to use FIND command and search for logs old then 7 days
17) How to block the IP address in Linux

## Shell Scripting
1) Write a shell script to fetch the data from rest API and take out the required Fields
2) Write a shell script to extract the number of alphabets characters and digits and tell the count
3) Write a shell script to extract the IP addresses from a file and the count of similar ipadress
4) Write a shell script to hit the rest API and modify the json data and put it back to the database
5) How to declare an array in shell script
6) What is crontab and tell some time set you have done
7) Why do we give #!/bin/sh at start of shell script
8) Write a shell script to find old logs and archive it
9) What is `$#`,`$?`,`$@` etc.. in Linux shell script

## Ansible
1) What is Ansible architecture
2) How a normal yaml file is different from Ansible playbook
3) What is Ansible playbook, define all terms in playbook
4) What is handlers and notifiers
5) What are registers
6) What are various modules you have used in Ansible
7) How to used when condition and loops in Ansible
8) Write a playbook to start a service, stop a service and check the health check of service
9) What are Ansible adhoc commands
10) What are roles and tell where you will keep the different files in different folders
11) What is Ansible vault and how you store the secret files
12) How the SSH connectivity takes place between two server in Ansible

## AWS
1) What is VPC and its components (Public, private, NACL, Route tables, Internet gateway)
2) What is difference between NACL and Security groups
3) What is different types of load balance and tell difference between Network and application
4) What is route 53, types of routing policy and routing used
5) What is ASG and Launch config
6) How to restore the login into EC2 if **pem** file is lost
7) How to encrypt the unencrypted AMI
8) What is EBS and EFS
9) What is VPC peering and VPC endpoint
10) What is S3 ? Types of S3 bucket? S3 bucket policy? S3life-cycle policy
11) What is IAM roles and how the cross region roles work
12) How to tell one EC2 to talk to other EC2 in other region
13) What is MySQL/Aurora Backup plan
14) What is CFT template & how a resource depends on other resource
15) What are important components of CFT
16) Which is faster storage EBS or S3? and Why?

## Docker
1) What is docker architecture
2) What is docker life-cycle
3) What is dockerfile and docker compose file
4) Explain various layers in a dockerfile
5) What is docker networking and tell various types of network in docker
6) What is default network in docker
7) How one container talks with other container
8) How to debug the container
9) What is docker swarm
10) Tell some commands in docker
11) What is difference between `ADD`/`COPY`, `CMD`/`ENTRYPOINT`, `RUN`/`CMD`
12) Tell the docker file best practices
13) How to reduce a docker file size
14) How to store the docker file in jfrog/docker-hub
15) How to create a docker image if no internet connectivity is there
16) Write a docker file and state various layers and use the `depends_on` concept
17) How to save a container as image and then as a zip file
18) What are docker volumes

## Kubernetes
1) What is the architecture of Kubernetes
2) What does control manager, etcd, scheduler, API server do
3) What is a manifest file and what are the components of it
4) What is node affinity, pod affinity , taint toleration
5) What is node port, cluster IP
6) What is persistent volumes and why we use it
7) Describe what is pod and what is pod life-cycle
8) What are the components on master and worked node
9) What is ingress controller
10) What are types of services in Kubernetes
11) How one pod talks with other pod
12) How the pod healthcheck is done(describe Readiness, Liveliness)
13) How the monitoring is done(integration on Prometheus and grafana)
14) What is deamonset, replica-set, horizontal pod autoscaler
15) Write a manifest file of your own choice
16) What is Namespace and why we use it
17) What are helm charts and uses

## Cicd
1) Tell the design of CICD in your organization
2) What are various plugins in your Jenkins
3) What is difference between declarative and scripted pipeline
4) What is a groovy file and write groovy script what you have worked on
5) How each tool is integrated with Jenkins
6) Tell me the shell scripts used in Jenkins
7) How the auto increment of version is done in UI and MS
8) What is global credentials and how to make the passwords
9) What is sonarqube and how you define the thresholds

## Gitlab
1) What is branching strategy used
2) How you make the push rules, access level grants
3) What is git pull and git fetch difference
4) What is git stash and git rebase
5) What is git revert
6) What is cherry pick
7) How you resolve the merge conflicts
8) What is git clone
9) How you designed your Gitlab CI
10) What is difference between Gitlab and GitHub
11) How the Jenkins talks with Gitlab

## Security/Monitoring
1) What is SAT and DAST
2) How fortify rules are placed? Can we changes the rules
3) Different types of fortify errors and resolution
4) Black-duck errors
5) How the new relic is integrated with each micro-service
6) What is SLO,SLI, SLA
7) What are the different dashboards created in New relic and Grafana

## Design Diagrams
1) Jenkins pipeline
2) AWS architecture

## Managerial Questions
1) Tell me what was your most difficult situation you faced and you resolved
2) When you had issue with your management and how you convince them
3) How you have helped your peer
4) Did you got a chance to convince customers for your work
5) How the Jira tasks are assigned to your team
6) Tell me what your manager told negative point about you
7) Tell me you put time significant outside your work
8) Critical feedback from colleague and you worked
9) Give me an example of calculated risk where speed was critical
10) You worked on deadline and did not had options before taking decision
