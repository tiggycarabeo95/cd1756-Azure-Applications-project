# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

I believe that the an App Service would be more suitable for this development. The App Service is a managed platform so it is faster to deploy and easier to manage. It also already has a ready connection to SQL database and Blob storage, as well as built-in authentication to Microsoft Entra ID.  It also offers to option to scale up/down easily and you only need to pay for what you need so it is also more cost-efficient. 

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

Going for the Virtual Machine would be justified if the application requires a full operating system control or custom needs like specific authentication or security constraints. 
