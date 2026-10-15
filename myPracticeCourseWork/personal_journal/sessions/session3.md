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

3.1-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

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

3.2-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="590" height="130" alt="exercise 3 2 first 2" src="https://github.com/user-attachments/assets/72656399-6937-474c-9143-19086dbe24c8" />

shows local dns configuration within the ansible controller, very effective due to mapping out the hostnames and recording it as a IP address so user and i can idnetfy  which  machines we want by  the names of the devices instead of remebrering the ip address . 

<img width="938" height="248" alt="exercise 3 2 first 3" src="https://github.com/user-attachments/assets/aef3cd99-024b-4d05-967a-d59c79d6021c" />

This image shows that I have successfully implemented  ansible playbook on the two virtual machine this also shows that within this playbook it has configuration  of dns.

<img width="745" height="334" alt="exercise 3 2 first 4" src="https://github.com/user-attachments/assets/f7162a8b-d209-4469-8214-bc1c101af952" />

DNS resolution is working for both virtual machine ubuntu internally and externally.

<img width="557" height="317" alt="exercise 3 2 first 5" src="https://github.com/user-attachments/assets/0cc6d8d9-3aa2-4910-a7f5-e48eb5ad50e8" />

I have SSH into my  ubuntu virtual machine from ansible controller. SSH is very effective provides a secure communication with the IP address of the VM. This also shows that the SSH key is implemented which helps provide a strong security, overall it shows the remote connection is working.

<img width="695" height="150" alt="exercise 3 2 first 6" src="https://github.com/user-attachments/assets/b93725c7-a9ef-4754-a40e-bab9914390aa" />

This images shows that DNS server is working effectively ,port 53 manages DNS quire supporting by TCP allows larger response to take place this screenshot shows the IP address has been given a domain name useful for user as they can request what webpage they wat to use by entering the domain name rather then knowing the IP address .

3.3------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="868" height="470" alt="exercise 3 3 first 1" src="https://github.com/user-attachments/assets/c5e90a16-5339-4021-8cc9-9aa35e3defd9" />

This shows that I am running the ansible playbook which is a file that is filled up with configuration and what to downloaded and install it has successfully implemented  DNS server with no packet being loss or failed.  

<img width="562" height="255" alt="exercise 3 3 first 2" src="https://github.com/user-attachments/assets/8e853134-3476-4626-8f8b-83042507bba0" />

BIND9 has been installed and is running with no error.BIND9 is very useful as it helps converts the domain name into IP address 

<img width="597" height="521" alt="exercise 3 3 first 3" src="https://github.com/user-attachments/assets/b39ac1ad-4097-4be6-83fc-1a6c5d8b09fe" />

I have started  the testing of DNS within the ubuntu machine I have used the dig command to help me find the IP address that is associated with domain name.

<img width="431" height="226" alt="exercise 3 3 first 4" src="https://github.com/user-attachments/assets/ec095a77-26e1-4664-887d-ed65c548976a" />

The DNS server at 192.168.100.250 is successfully fixing google.com to ipv4 address

## Summary of learning
*What did you learn through these exercises*

I have learned how to configure DHCP and DNS server using ansible controller. I also learned how to test and make sure they are all running by using commands such as dig.  
