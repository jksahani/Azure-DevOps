**Azure Pipeline Docker build and Deploy to WebaApp**


Docker --
ACR --
Webapp --
Pipeline ---

Compose Docker file --

Docker ? ?

Docker Desktop --- Docker Desktop 
Docker Hub -- Image rgistry 
Docker Swarm -- Orcstration 

Dev + Docker Desktop + Compose --

Repo --> Docker build --> Send to ACR --> Deploy to Webapp/AKS -- 


Created a repo ---> Pushed Web containts ---> Created Service connection for Docker hub ---Created Docker file ----> Created Pipeline and added the below docker task:-

- task: Docker@2
  inputs:
    containerRegistry: 'jksahani-docker-hub'
    repository: 'jksahani/web01'
    command: 'buildAndPush'
    Dockerfile: '**/Dockerfile'


**Deployment to the Webapp**

Create Webapp (container)
 