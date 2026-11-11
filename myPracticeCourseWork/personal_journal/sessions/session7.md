[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 7

## Topics covered
*What topics were covered in this session*

We have learned how to use and implement  monitoring  applications such as Open NMS  which helps mange's the network CPU , ram Ip address etc .Shows data in a format of graph tables with also learning how to use and configure semaphore installing Apache and uninstalling  Apache 


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
I have completed exercise 7.1 and 7.2

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
7.1

<img width="956" height="536" alt="week 7 " src="https://github.com/user-attachments/assets/bfd8bb9e-5983-49cd-b369-701195ff946e" />

This screenshot shows that Open NMS horizon dashboard. It gives us a overview status of the network infrastructure , such as network interface and web server. If there is a error within a network or infrastructure an alarm can be used and set 


<img width="466" height="295" alt="week 7 2nd" src="https://github.com/user-attachments/assets/68d61fb9-921d-4727-92de-42507ba6635a" />

This image shows the Open NMS availability table over 24 hours as you can see network interface says 100% availability meaning they are working

<img width="792" height="508" alt="week 7 3rd" src="https://github.com/user-attachments/assets/58984f50-72e8-4a12-9488-390d8d0c0757" />

<img width="833" height="374" alt="week 7 4th" src="https://github.com/user-attachments/assets/ab9971f6-c751-4a27-b006-52cfe030e8b2" />

These two images shows a correct ping  connectivity between  the two network devices from inside the Open NMS docker container. We have used the command ping net SNMP which is successful

<img width="394" height="394" alt="week 7 5th" src="https://github.com/user-attachments/assets/163fbb80-eea0-4c2b-97ae-23d53c7fe27f" />

<img width="395" height="395" alt="week 7 6th" src="https://github.com/user-attachments/assets/addaedd9-312b-45c8-999f-4f0b0d7cf852" />

This screenshots shows that i have implemented the other network interfaces adding a range to discovery page using Open NMS provides a automatic scan discover devices such as switches router .The main purpose of these two images it to configure distributed network discovery. With the second range assigns discovery to minion1 the range to minion 1 -location allows minion associated with that location to perform discovery. 

<img width="395" height="395" alt="week 7 6th" src="https://github.com/user-attachments/assets/e81650da-cb00-438a-a2f2-4e771334393a" />

<img width="956" height="506" alt="week 7 8th" src="https://github.com/user-attachments/assets/f7218254-f42e-481c-96da-d94f8ad083a9" />

The first screenshots shows the list of interface on  the network such as the router ,switches devices etc it shows that Open NMS discover 12 interfaces with the second image the indvovual descprtion of the node such as details of its ip address particular node that u want to monitor

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

exercise 7.2

<img width="959" height="511" alt="week 7 exercise 7 2 1" src="https://github.com/user-attachments/assets/4c3e83c5-fb75-4962-963c-fa9e0529bffe" />

As you can see here to start and run files i made sure the formatting is corrcet and signfcant by using nano to remove the unwanted formatting or hideen chratcater i dont want.

<img width="951" height="292" alt="week 7 exercise 7 2" src="https://github.com/user-attachments/assets/adedefac-b8e8-48f1-8bac-2e1224cf78d0" />

This screenshots shows that alma Linux , Ubuntu 24 and 10 docker images were successfully created and built with multiple container's and a docker were created. The semaphore is a type of monitoring application that resolve error before expansion. 

<img width="952" height="532" alt="week 7 exercise 7 2 3" src="https://github.com/user-attachments/assets/701b998f-0645-4ace-8fa0-8140fdbfebad" />

<img width="958" height="532" alt="week 7 exercise 7 2 4" src="https://github.com/user-attachments/assets/d72e0044-6c76-46f1-a6a6-1cdb0e6903d8" />

<img width="949" height="530" alt="week 7 exercise 7 2 5" src="https://github.com/user-attachments/assets/2ce22ab2-0e04-423d-9b36-082fb4beef91" />

This screenshot shows that Apache web server is installed successfully using ansible through semaphore UI. The task is also a success meaning the execution of the log of install -Apache - with - pass is successfully installed on Ubuntu and almasd1.The semaphore task template shows the dashboard of other tasks to make sure the Apache web server is installed. To verify the connection of Apache web server  we enter the localhost8084 on a web browser and it shows a efficient webpage test of showing the installation is complted.

<img width="954" height="533" alt="week 7 exercise 7 2 6" src="https://github.com/user-attachments/assets/96182a83-1c4d-437a-af07-29ed3515519f" />

<img width="894" height="525" alt="week 7 exercise 7 2 ubntu uninstalled" src="https://github.com/user-attachments/assets/ff5a3195-29f0-4f9c-ba15-c2cbeaa06989" />

shows that i have successfully removed the ubuntu web server from host 8084

<img width="938" height="489" alt="week 7 exercise 7 7" src="https://github.com/user-attachments/assets/646bb6f4-0dc2-4d6a-bf2b-4ff8f6cfec39" />

This ss shows the ansible playbook task configuration page lists all the repository ,inventory path of playbook and more allows us to customise and execute paths we wanted.  

<img width="950" height="527" alt="week 7 exercise 7 2 9" src="https://github.com/user-attachments/assets/b8a2bbb1-4d24-4830-a7a7-0bde223cb50c" />

I have ran all the task are the have successfully done what was expected by the playbook




## Summary of learning
*What did you learn through these exercises*
