# Background
A development team has created a Java web app that is ready for a limited release (with reduced availability and reliability requirements).  If the limited release is successful the app will be rolled out for worldwide use.  Once fully public, the application needs to be available 24/7 and must provide subsecond response times and continuity through single server failures.

## Basic problem
You need to create two environments one for **training** and one for **production**.  You should prepare the production environments for the limited release and plan for the scale-out during the full public release.


# Assumptions
* We want to evaluate your skills in Configuration Management tools like `Chef/Puppet/Ansible`. So please make sure you use one of these tools.
* The development team has a continuous integration build that produces two artifacts:
  * a `.zip` file with the image and stylesheet used for the application
  * a `.war` file with the dynamic parts of the application
* You should deploy the static assets to a web server and the .war file to a separate application server. Any compatible servers are acceptable.
* The app (CompanyNews) uses Prevayler for persistence.  Prevayler essentially persists data to a file. The dev team chose this to simplify the development effort, rather than having to deal with an RDBMS.

# The expected output for this problem

Simply put, we want you to design and create the training and production environments, and provide a plan to scale out that deployment when the application goes public.
You can use a virtualization solution such as VirtualBox or a cloud solution like AWS for these environments. We do not want you to deliver the VMs to us.
Instead, you should provide a script to enable us to build these environments ourselves (without manual intervention).

We should be able to provide the necessary configuration to the script and deploy the application to `VirtualBox/EC2` from our workstations.

## 🛠 Skills
Ansible, Chef, Puppet, Linux, DevOps.

## Authors

- [@akhan4u](https://www.github.com/akhan4u)
