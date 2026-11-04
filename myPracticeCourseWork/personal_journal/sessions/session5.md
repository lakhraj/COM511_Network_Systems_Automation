[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 5

## Topics covered
*What topics were covered in this session*

-In todays lab we have covered  the basics of Docker how to installed it, running a docker container and also building a docker container.
-We also covered how to run and build a docker container in ubuntu using vagrant 


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

I have completed exercise 5.1 and 5.2

5.1 exercise 

<img width="959" height="554" alt="session 5  2 " src="https://github.com/user-attachments/assets/eedc99ed-d90b-455d-8fd3-ea484290be78" />

As you can see within this screenshot it starts a simple ubuntu container on PowerShell. This command basically represent a download of the ubuntu 22.04 

<img width="958" height="568" alt="session 5   3" src="https://github.com/user-attachments/assets/aad897e1-3239-480c-97e0-cc3c7957dc48" />

As you can see within this screenshot it shows the process of managing ubuntu docker on PowerShell. The command docker PS shows a listing of the current containers that are running. The command docker exec -it e66a71745c45 bash opens a bash terminal inside that specific container. The command docker ps -a shows all the current containers that are stop. Docker run -it -d -p 8081:80 --name ubuntu1 ubuntu:22.04 provides a named ubuntu container mapping the host port 8081 to container port 80.Overall these command shows how to create ,access ,inspect and stop docker container running ubuntu.  

<img width="959" height="564" alt="session 5   4" src="https://github.com/user-attachments/assets/9d7b1095-4de8-4b6d-a13a-47ed8dd4eddd" />

This screenshot shows apache2 is installed, as you can see on the web browser the message "It Works" shows Apache is operated on a webpage successfully. The address local host 8081 shows that the browser is connecting to a service on port 8081 on your own computer.

<img width="949" height="383" alt="session 5   5" src="https://github.com/user-attachments/assets/3e9f36b1-c6ae-4433-9359-6d679793e9c0" />

The command docker build -t my-Apache builds a  docker image using the instruction provided by the docker file located at the current directory.

<img width="959" height="562" alt="session 5   6" src="https://github.com/user-attachments/assets/c15a52aa-0e8f-44c2-9079-bda873db1e1a" />

<img width="945" height="560" alt="session 5   7" src="https://github.com/user-attachments/assets/34a5bcb5-6cbb-457e-b124-a10a7515da4d" />

this shows that Apache is installed and successfully  on the different ubuntu machine as they both have a different local hosts represented. Two container are created  and can be access using http local host.

<img width="959" height="118" alt="session 5  8" src="https://github.com/user-attachments/assets/fb3e4870-4f5e-4283-88e6-883fdd1bfe98" />

This image shows us that both container are running with the time and status of each container ID

<img width="954" height="166" alt="session 5  10" src="https://github.com/user-attachments/assets/057028d0-499d-4dd7-b4ed-4d39d92af8df" />

It is very efficient to remember that even though the container has stop they  still can be  presented  on the file system. Which can have a negative impact as they use a lot of space within your personal  disk without you knowing. Therefore to remove them the command docker rm this helps remove one stopped container to remove all the stop container u use the command docker container prune. 


5.2 Exercise

<img width="939" height="406" alt="session 5 exercise 5 2 2" src="https://github.com/user-attachments/assets/78ce50a1-3627-4c37-99a5-8e79e64f8425" />

i have successfully built a docker image for Apache on my vagrant Linux virtual machine.

<img width="915" height="557" alt="session 5 exercise 5 2 1" src="https://github.com/user-attachments/assets/c12fb8a9-e02f-49d7-bf3a-126c87590a57" />

The browser screenshot shows the Apache home page provides a clear evidence that the web server  is accessible at the http link. 


## Summary of learning
*What did you learn through these exercises*

I have learnt how to create container build a docker container as well  with running it and linking my Linux virtual machine to docker.
