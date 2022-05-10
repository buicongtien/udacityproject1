# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

App Service: It is more cheaper to run in comparison to Azure VM. The CMS app is lightweight, therefore deployed through an App Service are reasonable 
             and no need significant compute capability.
             The development of app is much simpler and faster in Azure App Service.
             App Service do not offer Pay-as-you-Go. Hence, you’re paying for the service plan, even if you’re not using it.
             and there may be constraints for the support of certain programming languages on Azure App Service.
             But it very useful for teams with less manpower, and less experience with managing such hardware.

Virtual Machine: It are more expensive to run in comparison to Azure App Service, but user can shutdown VM when no need use to save cost.
                  The VM allows for more customization of the app's capability.
                 Azure VMs offer developer more control over the environment.

My Choise: App Service. Because CMS app is very lightweight no need for a powerful server and App use Python language that App Service have support. 
           It also support continous deployment through GitHub workflows that makes updating the CMS app a snap.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

App Service: If the CMS app become more bigger and need more complex features that would require more hardware, the costs could rise quickly.

Virtual Machine: If the CMS app become more bigger, Developer need require more harware that can make cost become significantly more expensive.
                 Managing and updating Vm is also very complicated