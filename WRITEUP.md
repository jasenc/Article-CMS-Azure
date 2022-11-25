# Write-up Template
## Jasen Carroll
### ArticleCMS - Azure Developer

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

#### Virtual Machine: ####
Costs: The costs of virtual machines typically is more than using an app service.
<br />Scalability: Multiple VMs can be grouped to provide high scalability, though this would have to be done by someone who knows how.
<br />Availability: Multiple VMs can be grouped to provide high availability, , though this would have to be done by someone who knows how.
<br />Workflow: The workflow is typically completely manual or whatever you're willing to automate on your own/with other services.
#### App Service: ####
Costs:
<br />Scalability: limited scalability could be an issue with how popular the app gets given the hardware limitations.
<br />Availability: highly available, auto-scaling, and support of both Linux and Windows environments.
<br />Workflow: The workflows are highly automated and can be much easier to work with for those with limited technical backgrounds. Limited to whatever languages are supported.

#### Chosen Solution & Justification ####
For this ArticleCMS the App Services was chosen. The point of this exercise is to familiarize myself with Azure and not build a virtual machine from scratch, which I have previously done thanks to a different Udacity course :).

### Assess app changes that would change your decision.
*Detail how the app and any other needs would have to change for you to change your decision in the last section.*
- If it were decided to re-engineer the webpage using the Go language, App Services would not be an option.
- If the platform were to get big enough, we would want to consider vitual machines and hiring on the necessary competency and hardware to scale our own platform operations - while still using Azure as our IaaS.
- Etc. 
