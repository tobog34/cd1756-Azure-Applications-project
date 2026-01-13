# Write-up 

### Analyze, choose, and justify the appropriate resource option for deploying the app.

In deciding between whether to use a VM or App Service for an application, four main areas must be considered. Those areas are cost, scalability, availability, and workflow. VMs allow far more flexibility than App Services as you have control down to a more granular level with the OS. However, this takes more work, experience, and cost to set up as opposed to an App Service. App Services are built for easy auto scalability that would require more work to duplicate with a VM setup. Both options should have similar availability as cloud providers typically have very high uptime rates. The workflow to setup an App Service is far simpler than one to setup a VM. For this application, I chose to use an App Service since it provides the simplest workflow and the project does not require a large degree of control down to the OS level


### Assess app changes that would change your decision.

If the project needed to use multiple languages or required processes that needed specific hardware then I would likely switch to using a VM. Additionally, if I were migrating from an on premises server to the cloud, a VM would be appropriate. I would be able to duplicate the entire setup on a VM, which would not be possible on an App Service

