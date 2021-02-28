---
layout: post
title: Getting started with Hypervisors
---


Hypervisor basically stands for a software that lets you run one or more virtual machine on your system.It is also called a VMM(Virtual Machine Monitor).
Vmware and hyper-V are examples of hypervisorss

##Types Of Hypervisors
The following are the types of hypervisors:

 ###Type 1
 Baremetal hypervisors or native hypervisors are directly installed on the host as a light OS, it does not require a base OS to be installed on the machine.The baremetal hypervisor 
has direct access to the CPU ,RAM and other system resources which make the pretty fast and efficient.Since, the hypervisor is directly involved without an  attach prone 
Operating system, its relatively secure.
A few examples of Type 1 hypervisor include Oracle VM, Microsoft Hyper-V etc.
 
##Type 2
It runs as a software on the OS of the host machine,thus are often called hosted hypervisor.Examples of this type of hypervisor include vityalbox, Vmware Workstation etc.
Unlike baremetal hypervisor which can dynamically allocate system resources like memory or CPU time to vm's , in this type only memory allocated to the vmm will be used .

There are some hypervisors like linux KVM which acts like a kernel module and turn the os into a hypervisor.

