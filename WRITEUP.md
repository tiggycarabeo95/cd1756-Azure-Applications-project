### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

<img width="1168" height="357" alt="image" src="https://github.com/user-attachments/assets/54886781-35d8-4ee3-b962-a079b831ba0b" /># Write-up Template

I believe that the an App Service would be more suitable for this development. The App Service is a managed platform so it is faster to deploy and easier to manage. It also already has a ready connection to SQL database and Blob storage, as well as built-in authentication to Microsoft Entra ID.  It also offers to option to scale up/down easily, as needed, and you only need to pay for what you need so it is also more cost-efficient. The base price for the App Service is also much cheaper compared to the Virtual Machine option. Since the requirements for this application are quite simple (i.e. create web page that requires log-in and can publish articles) and these can be done through tools that are available with the App Service, it is more practical to go with that option.


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

Going for the Virtual Machine would be justified if the requirements for the application would become more complex. If it requires a full operating system control or custom needs like specific authentication or security constraints, this would justify the option for going for the Virtual Machine route. 
