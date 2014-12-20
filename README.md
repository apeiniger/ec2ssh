ec2ssh
======

A tool to easily login to EC2 instances or run commands on multiple instances at the same time

You need to have the aws cli tools installed in order to use this script.

To log into a EC2 instance you need to follow these steps:
1. Run "ec2ssh"
2. Enter the path to your ssh private key for logging in (this only needs to be done once)
3. Choose the instance(s) from the list provided by typing the number of the instance at the prompt. If you want to run a command on multiple instances, enter the numbers comma separated.
4. You will be either logged in to the instance you selected or you will get another prompt to enter a command to be run on the instances.

Let me know if you are having any difficulties by opening an issue here.

Alex
