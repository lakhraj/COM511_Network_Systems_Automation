[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 2

## Topics covered
*What topics were covered in this session*

-We have learned about vagrant and its virtual machine.I have created 3 virtual machine which consist of ubuntu server, rocky Linux and ansible controller.
-Developed and checked the networking by using ping to test the connectivity
-We manages to use SSH which is very secure I connected ubuntu and rocky server using SSH
-We also logged into the ansible controller which allows us to run commands and playbooks 
-We worked in ansible controller inventory  


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

to commit work use
```
git add --all
git commit -m 'some message'
git push
(ente4r your passphjrase)
```

## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

Todays session I have completed exercises 2.2 , 2.3 and 2.4

Exercise 2.2

![test](../images/exercise%202.2%20first%201.png)
As you can see this shows that I have used the command vagrant up which allowed me create 3 virtual machine ubuntu_1 , rocky_1 and ansible controller. Shows that all VM are running. I have gain access to ansible controller by SSH which allows me to remotely mange other VM with ansible. I  made sure I was in the correct VM by using the command hostname 

![test](../images/exercise%202.2%20first%202.png)
It shows the ip address of each virtual machine within the network for example rocky Linux Ip address of the vm is 192.168.56.30 so I made sure to ping it which was successful  this allows communication between ansible take place.

![test](../images/exercise%202.2%20first%203.png)

This image shows how I have successfully connected ubuntu VM with the ip address of 192.168.56.20 using SSH as the ansible user  

![test](../images/exercise%202.2%20first%204.png)

This images basically shows I have successfully connected rocky Linux VM With the Ip address of 192.168.56.30 using SSH as the ansible user 

exercise 2.3

![test](../images/exercise%202.3%20first%201.png)

I have SSH into ansible controller making me a user allowing me to able a ping command allowing me test connectivity 

![test](../images/exercise%202.3%20first%204.png)
This images suggest to us that ansible is working effectively on the main/control machine .all 3 VM was successful the pong suggest to us that ansible can connect and execute a module on each Virtual machine. Overall shows that communication can take place. The command is very effective as it tells us whether ansible can connect to every machine in the inventory successfully.

exercise 2.4

![test](../images/exercise%202.4%20first%204.png)

![test](../images/exercise%202.4%20first%205.png)

These two images shows that ansible successfully used one playbook to install and configure Apache on three virtual machines. Being able to automatically know the operating system  



## Summary of learning
*What did you learn through these exercises*

i have learned how to be a user on ansible VM i used the commands vagrant up to make the VM is running i made sure to run ip addr which allows me to see the Ip address of the VM which is important as i will know where to start  pinging and what devices i want to be on.I have also learned about accessing ansible using SSH for security and protection with installing Apache on the three VM with playbooks



