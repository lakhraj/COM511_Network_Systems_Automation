[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 8

## Topics covered
*What topics were covered in this session*

-Introduction to Kubernetes.

-Docker Compose vs Kubernetes.

-Kubernetes architecture.

-Pods, Deployments, ReplicaSets and Services.

-Kubernetes cluster setup using Docker Desktop.

-Basic kubectl commands.

-Deploying and managing applications.

-Load balancing, scaling and self-healing.

-Kubernetes YAML configuration files.


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

i have completed exercise 8.1 and 8.2
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
8.1

<img width="856" height="287" alt="Screenshot 2026-11-18 112440" src="https://github.com/user-attachments/assets/c66e9265-f0b7-4005-9e1a-ab15b0d3138a" />

The first screenshots shows a simple deployment Within the deployment it defines one or more pods which contain containers, with information about the running system.

<img width="959" height="563" alt="Screenshot 2026-11-18 112547" src="https://github.com/user-attachments/assets/04b38f34-6e7e-46dd-a1c7-7eb1bd6e14f9" />

This screenshots shows and describe a particular pod using the name. This gives us all of the details of the pod 

<img width="958" height="557" alt="Screenshot 2026-11-18 112716" src="https://github.com/user-attachments/assets/90aa3471-0f0e-44c6-999f-b0e80a581554" />

We can also look at the logs in a particular pod 

<img width="953" height="563" alt="Screenshot 2026-11-18 115007" src="https://github.com/user-attachments/assets/1fcdd4ab-d606-4f44-9d23-49d57aab4368" />

The expose deployment command allows us to identify  the service through a load balancer within http:/localhost:80/

<img width="954" height="185" alt="Screenshot 2026-11-18 115138" src="https://github.com/user-attachments/assets/e430210c-8a11-489f-8405-5bcdc4e77ece" />

This screenshots has a mixture of commands kubectl get pod deletes the pod , a new one will be created by the replica set in the deployment. However to stop the service we need to delete the deployment 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

8.2 

<img width="950" height="558" alt="Screenshot 2026-11-18 120120" src="https://github.com/user-attachments/assets/50e44a2b-a015-4405-9bc8-6ad6f405c2cc" />

This screenshots shows a docker image is being installed 

<img width="935" height="119" alt="Screenshot 2026-11-18 120202" src="https://github.com/user-attachments/assets/3c57cbff-4231-4d58-b8c2-7c05f4cfde01" />

shows i have successfully  installed Kubernetes demo app using docker with three available endpoints  

<img width="959" height="565" alt="Screenshot 2026-11-18 120313" src="https://github.com/user-attachments/assets/44de3611-311a-4296-acaf-7ac1d8e2659f" />

K8s Demo App is successfully running and accessible through your web browser at http://localhost:3000.

<img width="947" height="400" alt="Screenshot 2026-11-18 120741" src="https://github.com/user-attachments/assets/78e7e60b-4d2e-41e6-9b46-6d9483911c95" />

This screenshot shows a deploy to Kubernetes 

<img width="956" height="548" alt="Screenshot 2026-11-18 121650" src="https://github.com/user-attachments/assets/d0cfc522-9e33-4d4c-a702-347594efff15" />

This screenshots shows an access to the application at http:/localhost:80 with commands showing the views of resources 

<img width="957" height="194" alt="Screenshot 2026-11-18 122504" src="https://github.com/user-attachments/assets/7314b9fe-ebfc-4b63-a083-22ff9fe53e4c" />

This screenshots enables manual scaling and also allows me to see more pods 

<img width="947" height="557" alt="Screenshot 2026-11-18 122739" src="https://github.com/user-attachments/assets/85218df2-e0bb-44de-9b48-298ebdfb74c3" />

K8s Demo App health check endpoint is working successfully. It confirms that the application is responding to health-check requests.

<img width="959" height="553" alt="Screenshot 2026-11-18 122818" src="https://github.com/user-attachments/assets/d6142514-8b88-445c-ae43-f41bde6c8055" />

It displays information about the running application in JSON format.
## Summary of learning
*What did you learn through these exercises*
