# Background

We want to automate the deployment of MediaWiki on AWS cloud on CentOS.

## Deployment Topology
 * We'll have two instances of MediaWiki running on two `t2.micro` EC2 instances
 * These will be load balanced using HAProxy on one `t2.micro`
 * They'll be backed by a MySQL server running on a separate `t2.micro`

# Details

We expect this to be installed using these steps automated using an automation tool of your choice (`Chef/Puppet/Ansible`). The automation tool will be running on another `t2.small` instance, from where the deployment happens.

# The expected output for this problem
In this process, we want to assess your learnability and your current knowledge of config management systems.

This solution will be used by developers on your team who don’t have any knowledge about configuration management tools/ cloud access. So we expect a script that automates the deployment to various environments

While you can draw inspiration from the open-source cookbooks/modules, you will have to write all the modules including httpd, MySQL, etc. on your own.


## 🛠 Skills
Ansible, Chef, Puppet, Linux, DevOps.

## Authors

- [@akhan4u](https://www.github.com/akhan4u)
