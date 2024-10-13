# Testing-Weak-Password-with-John-the-Ripper

For this project, the goal is to provide a comprehensive guide on setting up John the Ripper on an Ubuntu machine in Azure. The guide will walk users through the installation process, demonstrate how to test weak passwords for vulnerabilities, and highlight the importance of implementing strong password policies. This project is aimed at enhancing both the security knowledge of the audience and their technical proficiency in using John the Ripper as a password-cracking tool. Additionally, the project will emphasize proactive password management practices to help users secure their systems against brute-force attacks.

If you need help on how to spin a Linux vm in a cloud environment, Please [click here](https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal?tabs=ubuntu)


Here are the following steps: 

 1. Install John the Ripper:

 
     Run the Following Command: sudo apt-get install john -y
<p align="center">
<img src="https://imgur.com/MX69ojf.png" height="80%" width="80%" >

 1. Identify the disk:

     First, you need to identify the disk you want to partition. You can use the "sudo fdisk -l" command to list available disks and partitions:
     Run the Following Command: sudo fdisk -l
<p align="center">
<img src="https://imgur.com/uYSnwkH.png" height="80%" width="80%" >


 1. Identify the disk:

     First, you need to identify the disk you want to partition. You can use the "sudo fdisk -l" command to list available disks and partitions:
     Run the Following Command: sudo fdisk -l
<p align="center">
<img src="https://imgur.com/uYSnwkH.png" height="80%" width="80%" >


 2. Create a password file for John the Ripper to test on:

    Using "unshadow" command to extract account names and passwords.
     Run the Following Command: unshadow /etc/passwd /etc/shadow > password.file
<p align="center">
<img src="https://imgur.com/axb9AUy.png" height="80%" width="80%" >

 1. Identify the disk:

     First, you need to identify the disk you want to partition. You can use the "sudo fdisk -l" command to list available disks and partitions:
     Run the Following Command: sudo fdisk -l
<p align="center">
<img src="https://imgur.com/uYSnwkH.png" height="80%" width="80%" >
