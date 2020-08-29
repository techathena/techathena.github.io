---
layout: post
title: Application Whitelisting and Hellhound
---
We all have heard of blacklisting .Stuff we do with firewalls.Right?So, What is application whitelisting?           


Well, lets understand with and example.Say we have a network,we allow traffic from all addresses to enter it,and then block a few addresses ,then it is called blacklisting.Similarly if we block all traffic and allow only specific addresses in the network ,its called whitelisting.
    
# So what is Application whitelisting?
Again think you have a company,and your employees work on company systems,suppose all files can be exexcuted by default ,then it is possible that a malicious file can execute,since your antivirus is only blocking malicious applications from its database.Right?So we can implement an application whitelist and allow only specified applications to run.

# Okay then what is hellhound?

![image_tpm](https://raw.githubusercontent.com/techathena/techathena.github.io/master/images/hellhound.jpg)

Well,since I could not find many open source projects on application whitelisting, so I developed hellhound which is a prototype to implement application whitelisting in systems.
link to the project: (https://github.com/techathena/hellhound)
