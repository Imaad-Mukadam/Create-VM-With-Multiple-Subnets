# Create-VM-With-Multiple-Subnets

## Summary

This project involves creating an Azure Virtual Network (VNet) with two subnets:

HR Department Subnet

Sales Department Subnet

Two Virtual Machines (VMs) will be deployed, one in each subnet. The goal is to test whether the VMs can communicate with each other despite being in different subnets.

This will involve configuring network security rules, route tables, and IP addressing to enable or restrict communication as needed

## Steps - 1 

Select a Virtual Network

![image alt](1.PNG)

Configure the Basic Information

![image alt](2.PNG)

Now go into IP Addresses

i. Select the IP address class (Mine is Class C)

ii.Select the CIDR

iii. Now Click on Add a subnet

![image alt](3.PNG)

Creating HR subnet with 64 IP address Size

Click on Add button 

![image alt](4.PNG)

Similary Add Subnet of Sales Department

![image alt](5.PNG)

## Step - 2

Now Lets Create 2 VMs

i. Configure the Basic Information

ii. Then go to Networking

iii. Select the HR Subnet

iv. Click on Review and Create

![image alt](6.PNG)

Now lets Create 2nd Vm

i. Configure the Basic Information

ii. Go To networking

iii. Now Select the sales Subnet

![image alt](7.PNG)

