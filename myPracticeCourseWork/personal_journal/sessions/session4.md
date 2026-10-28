[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 4

## Topics covered
*What topics were covered in this session*
-vagrant PXE client/server environment which supports virtualbox providers.


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

I have completed only exercises 4.1 which consist of running PXE server and client to provide installation and partially exercise 4.2  

Exercise 4.1

<img width="439" height="410" alt="session 4" src="https://github.com/user-attachments/assets/8ea48828-3cfe-448b-b71a-039af3fd6098" />

This screenshot shows that PXE boot menu took place within the virtual oracle box it has three options which consist of 1. Install Ubuntu 24 from PXE HTTP (currently selected) 2. Install Ubuntu 24 from NFS PXE and 3.Local Boot.
I have chosen to use the first option which consist of downloading the ubuntu installer over HTTP. Overall this shows that the virtual machine is configured to boot from the network rather than ISO or local disk

<img width="892" height="554" alt="session 4  2" src="https://github.com/user-attachments/assets/069f16d2-35ae-4792-b0f5-033842e4f10b" />

This next screenshot suggest that PXE server setup is installed successfully. With also Ansible being configured. Ansible consist of being a tool that helps configure server and provide automation.

Exercise 4.2

<img width="892" height="521" alt="session 4  3" src="https://github.com/user-attachments/assets/c91180bb-f288-4c35-ab0a-cb16e654cb30" />

The PXE server Vagrant provisioning script has configuration of installing ansible and create an ansible user. I made sure verification was performed using ansible -- version this shows me that ansible was installed 


## Summary of learning
*What did you learn through these exercises*

Overall I have learnt how to install and  set up PXE server / client and to be able to create SSH key within the based authentication and configure ansible.

