**Azure Pipeline**


CICD --?

CI - Continuous Integration --> Code -->Build-->package--->push to Artifacts/ContainerRegistry 
CD - Continuous Deleivery/Deployment ---> Use the package and Automatikly deploy to the Servers/Clusters on varius environments(Dev,QA,UAT,Prod) 

AzureDevOps --
Pipeline (Build) ---
Release Pipleine ---

Pipeline - Set of tasks and automation. 

CICD - Continuous integration and Continuous Delivery 

1. Pipeline Setup Types -

Classic Pipeline (UI) ---Deprecate 
Yaml Pipeline (Code)

Terraform Repo-PR

2. Trigger (on/off)


.net code --->PR ---->start the build Build  /
Terraform code----->Trigger should be disabled--->Terraform deployment x

3. Build

4. Unit-Test

5. Restore 

6. SonarQube Scan 

7. Push package to the Azure Artifacts

CD ---

Release Pipeline 

1. Download the package 

2. Create the Secret

3. Deploy yaml file to the kubernetes

4. Review and finish


Deployment (Dev,Test,UAT,Prod)

Developement--->PR-->Merge with Master branch-->Triger the build---->Build--->Test-->Push the package to Artifact--->Start the Deployment---Dev Deployment---->Acceptance Test-->Test Deployment-->UAT Deployment---> Prod Deployment



1. Ecosystem--
2. everythings on a single dashboard
3. SAAS


Trigger --- Automated way to start the build 
Schedule time, 


-----------------------------------------------------

Pipeline 

Build Pipeline --- CI -- Build--Test---SonarScan--->push the artifact ---finish
Release --- CD ---download the artifact ---> Deployon the environment 

Service Connection --- 


Agent Pool --- 

Microsoft Hosted Agents(VM) ---Automated 
Self Hosted Agents(VM)  Azure/AWS/On-Prem


