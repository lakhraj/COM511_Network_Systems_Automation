[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 6

## Topics covered
*What topics were covered in this session*

-introduction to docker compose
-bulding docker images and using docker compose
-using pre bulit docker images
-Sharing external files and folders with containers (volumes).
-Using environment variables in Docker Compose.
-Running multiple containers together.

## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

I have completed exercise 6.1 
--------------------------------------------------------------------------------------------------------------------------------------------------------
example 6 - 1 done 

<img width="956" height="350" alt="session 6 example 6 -1" src="https://github.com/user-attachments/assets/9c583d6c-5e19-4c4f-be75-58e4d0efa601" />

This image shows that docker build is creating images on my-apache2  making sure it uses ubuntu 22.04 and installed Apache it is done successfully   

<img width="952" height="105" alt="session 6 example 6 -1 2nd photo" src="https://github.com/user-attachments/assets/157819a4-3681-45cd-bf7b-7e0045c91c4b" />

this screenshots shows the list of docker images stored on my computer

<img width="945" height="283" alt="session 6 example 6 -1 3rd photo" src="https://github.com/user-attachments/assets/e48c8a2f-666e-467e-a6f5-615fb8d7cb81" />

This image here shows that the two Apache web server containers have been successfully  deployed using docker compose overall it shows that both Apache containers are running successfully showing docker compose 

<img width="959" height="473" alt="session 6 example 6 -1 4th photo" src="https://github.com/user-attachments/assets/32f45cd5-bb8c-4e1a-9458-c2aca3f9d1e7" />

<img width="947" height="524" alt="session 6 example 6 -1 last photo" src="https://github.com/user-attachments/assets/8e0e65b2-fdc3-41c6-9d9a-48a168ddd688" />

This screenshots shows Apache 2 has been successfully installed, with a configured web page on both ports 8081 and 8082 
------------------------------------------------------------------------------------------------------------------------------------------------------------
example 6 - 2 done

<img width="950" height="228" alt="session 6 example 6 - 2 " src="https://github.com/user-attachments/assets/88058f3e-d016-4601-8d9e-52ff53c56797" />

Docker Compose successfully deployed two Apache web server containers.

<img width="959" height="437" alt="session 6 example 6 - 2 3rd page" src="https://github.com/user-attachments/assets/c55b5e3f-88da-41b1-a7b1-56751e036184" />

<img width="959" height="487" alt="session 6 example 6 -2 2nd page" src="https://github.com/user-attachments/assets/149e16fa-d6d3-4193-8cd3-8da7cd165640" />

These two images show that the two Apache web servers are functioning independently and successfully both Port 8081 accesses the first Apache container and Port 8082 accesses the second Apache container. Overall the Both containers successfully serve the generated example webpage.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
example 6 -3 done

<img width="950" height="186" alt="session 6 example 6 -3 " src="https://github.com/user-attachments/assets/069a2f75-d3b2-48b2-8ebb-8539628dc4de" />

This screenshot shows that docker compose has successfully deployed WordPress environment. This also shows that docker has successfully downloaded the relevant images, creating a docker network(MariaDB environment has been successfully created).

<img width="959" height="483" alt="session 6 example 6 -3 2nd photo" src="https://github.com/user-attachments/assets/8aa7bb03-c926-42cb-8c18-1033b1a8f679" />

<img width="936" height="449" alt="session 6 example 6 -3 3rd photo" src="https://github.com/user-attachments/assets/57f3a83f-7855-456c-ab28-301cae471de9" />

Within these two screenshot it shows that local WordPress website is running successfully through docker on my computer. We are able to login in using username and password to manage website ,create posts , install themes and customize the website appearance.

<img width="953" height="537" alt="session 6 example 6 -3 4th photo" src="https://github.com/user-attachments/assets/052ce3f5-fb19-4c46-83b9-de329a5a52af" />

This image consist work press admin dashboard I will  be able to mange the website obtain and sort the data of website and provide customizes the pages. Overall it provides us with a administrative control.

<img width="952" height="476" alt="session 6 example 6 -3 5th photo" src="https://github.com/user-attachments/assets/9f283c93-31d7-4e9f-9f89-e5fd5d99d4d8" />

the command docker compose exec WordPress 1 enables me to enter the WordPress docker container as a user in  which I can examine the files that are stored within the container such as using the command ls displays all the files. Docker compose logs -f WordPress 1 provides us with the request of user input continuously updates them as events occur. Monitor the the activity of the webpage.  

<img width="959" height="535" alt="session 6 example 6 -3 6th photo" src="https://github.com/user-attachments/assets/fd151e5a-de33-4c0e-87ae-ba6c97ba7711" />

This images shows the files and data of the MariaDB showing the startup logs 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
example 6 -4 done

<img width="953" height="232" alt="session 6 example 6 -4 " src="https://github.com/user-attachments/assets/682c24ad-517f-4e07-a670-076230a52f5d" />

This images shows that there is currently  3 WordPress that is running successfully  with a nginx which is a web server that host and Manges the request of user and stores website information 

<img width="947" height="477" alt="session 6 example 6 -4 2nd photo" src="https://github.com/user-attachments/assets/8e873c54-9ece-4b95-a795-439ac135353c" />

<img width="959" height="537" alt="session 6 example 6 -4 3rd photo" src="https://github.com/user-attachments/assets/be95a169-ab35-41c1-a26c-2b6d9c960f02" />

This screenshots shows that WordPress website is using docker however it is not very secure and can easily be hack and access. For example no HTTPS take place data can be easily tampered and hacked , with outdated WordPress version. 

<img width="941" height="559" alt="session 6 example 6 -4 last ss" src="https://github.com/user-attachments/assets/3cf69993-4b90-4b71-bae4-4d05a15b1103" />

This screenshots that I am using a monitoring setup to observe request going through nginx and the three WordPress. 






## Summary of learning
*What did you learn through these exercises*
