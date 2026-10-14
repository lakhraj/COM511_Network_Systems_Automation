[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 3

## Topics covered
*What topics were covered in this session*
-DHCP lease table
-DHCP Ansible playbook recap
-install dnsmasq
-local dns
-external dns
-bind9 ansible

## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

I have completed exercises 3.1 , 3.2 and 3.3

3.1

<img width="724" height="469" alt="exercise 3 1 first 1" src="https://github.com/user-attachments/assets/8c55c1b5-0f4c-434d-a00b-16a6bada70f2" />

Within this screenshot it shows that ansible playbook is successful. I have used ansible to configure DHCP effectively.Dnsmasq is running with the updated local DNS entries

<img width="631" height="30" alt="exercise 3 1 first 2" src="https://github.com/user-attachments/assets/07133858-f296-45c5-bddf-89354bce5b16" />

This images shows that there are IP address that are used for lease  within the network shows effective when managing the two VM ubuntu 

<img width="895" height="372" alt="exercise 3 1 first 3" src="https://github.com/user-attachments/assets/11b8ab1c-4087-4dde-851b-a99cff11174d" />

This screenshots shows tcpdump was very succecful.AS the request from the client and reply of the DHCP server was a success  this allows  devices on the local network  be  to have a working ip address set automnatilly  

<img width="696" height="134" alt="exercise 3 1 first 4" src="https://github.com/user-attachments/assets/135eefeb-86bc-4390-a6f8-d58d49b063a8" />

This image juts shows that dnsmasq is running without any error or problem 

<img width="594" height="200" alt="exercise 3 1 first 5" src="https://github.com/user-attachments/assets/355eb0d1-ad04-4e97-9e97-fb34bf874fc9" />

Within the two virtual machine ubuntu  1 and 2 shows they can successfully   ping and communicate with each other and allows ansible controller to have Ip address of the vms for communication. The ping responds with 4 sequence with no packet loss during the commuincation.

3.2

<img width="590" height="130" alt="exercise 3 2 first 2" src="https://github.com/user-attachments/assets/72656399-6937-474c-9143-19086dbe24c8" />

shows local dns configuration within the ansible controller, very effective due to mapping out the hostnames and recording it as a IP address so user and i can idnetfy  which  machines we want by  the names of the devices instead of remebrering the ip address . 

<img width="938" height="248" alt="exercise 3 2 first 3" src="https://github.com/user-attachments/assets/aef3cd99-024b-4d05-967a-d59c79d6021c" />

This image shows that I have successfully implemented  ansible playbook on the two virtual machine this also shows that within this playbook it has configuration  of dns.

<img width="745" height="334" alt="exercise 3 2 first 4" src="https://github.com/user-attachments/assets/f7162a8b-d209-4469-8214-bc1c101af952" />

DNS resolution is working for both virtual machine ubuntu internally and externally.


## Summary of learning
*What did you learn through these exercises*
