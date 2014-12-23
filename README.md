ec2ssh
======

A tool to easily login to EC2 instances or run commands on multiple instances at the same time

### Usage
To log into a EC2 instance you just need to run the script:

    ec2ssh

You can then enter the path to your ssh private key for login in (this only needs to be done once). Just choose the instance(s) from the list provided by typing the number of the instance at the prompt. If you want to run a command on multiple instances, enter the numbers comma separated. You will be either logged in to the instance you selected or you will get another prompt to enter a command to be run on the instances.

In order to avoid loading via the aws cli tool all the time, the script caches the instance list for 2 hours. If you are hitting the cache and need to refresh the list, you can use the --no-cache option mentioned below.

#### Options

    --no-cache            Ignore cache, load instances via aws cli tool and update cache afterwards

### Prerequisites

- AWS CLI tools need to be installed in order to run this script.
- PHP needs to be installed to run this script

### Misc
Let me know if you are having any difficulties by opening an issue here.
