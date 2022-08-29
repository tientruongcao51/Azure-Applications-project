# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
#### Cost

The App Service will have lower cost than VM.

#### Scalability

Both of VM and App Service have good choice for scalability. For VM we can scale the amount of VM. For App Service we can scale horizontally and vertically. Both have easy to setup the scalability. But, App Service will have more quick to scale than the VM.

#### Availability

Both of VM and App Service have high availability.

#### Workflow

If we have simple app, the App Service is the best choice, because we can set up easily for continuous deployment using GitHub, Azure DevOps, etc. Different with VM which have more complex steps before your apps online, as example, you need to setup the tools that you need to run your code, different with App Service that already provide you the tools.

VMs allow for the installation of custom images and are an excellent choice for migrating from an on-premises server to the cloud.

#### Solution/Choice for current CMS App

The best option for this CMS App is App Service. Allowing the developer to focus on app development while receiving less control over the deployment pipeline.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*

App Service are hardware limitations, such as a maximum of 14GB of memory and 4 vCPU cores per instance

We will need the VM if the app need to have high processor, as example need to have image processing (like image editing, image analysis, etc), video processing, etc.

![image](https://user-images.githubusercontent.com/32028093/187127558-2a1c6a1b-7e22-49c0-8435-62131b8eea13.png)
