# Josh Moulder  
  
**_Billericay, Essex_**  
**_+44 (0)7723389297_**  
**_Josh.Moulder12@gmail.com_**  
**_[https://uk.linkedin.com/in/joshmoulder](https://uk.linkedin.com/in/joshmoulder)_**  
**_[https://github.com/oimoulder](https://github.com/oimoulder)_**  
  
## PERSONAL PROFILE  
  
I have over 13 years’ experience working in various positions in busy technical environments. I have acquired a wide range of skills needed to solve problems from the simplest to the most complex and constantly continue to expand on these. I have experience working in small, medium, and enterprise sized business environments. I also possess good soft skills to compliment my technical skillsets.  
  
I am always looking for challenges to help me improve both professionally and personally. I possess the ability to prioritise and self-manage which has helped me to take initiative and be more multifunctional, I am comfortable both working in a team or individually to tight deadlines.  
  
## EMPLOYMENT HISTORY  

### Yell LTD
**_Senior DevOps Engineer_**
September 2022 - Present
Remote Working

- Working as a Senior member of the DevOps and Infrastructure team
- Leading various projects, including:-
    - Migrating DNS from internally hosted Windows and Linux servers to Cloudflare Enterprise, using Terraform to manage the DNS Zones, DNS Records, DDOS Protection Rules, DNSSEC, etc. for our business critical domains  
    - Designing and implementing Hashicorp Vault via the Hashicorp Cloud Platform, using Terraform, Ansible, and Bash scripts. Creating a full documentation library from High Level Designs and decisions, to nuances in the code, and guides for pieces of work that cannot be automated (for example - Secret Zero issue)  
    - Containerising our NodeJS builds in Jenkins due to NodeJS 14 and 16 end of life dates  
    - Planning and designing the new Jenkins environment, previously one big Jenkins Virtual Machine in VMware, to have one Jenkins Controller server with multiple service specific build agents  
    - Implementing Application Security, identifying insecure areas, working with developers to create an easy and unintrusive way to identify and remediate the security issues, investigating Snyk, Veracode, Github Advanced Security, SonarQube, SonarCloud, Semgrep, and more...  
    - Designing and implementing a VDI solution using Microsoft Azure for offshore employees
  
- Working on BAU tasks in the team to restore functionality, remove tech debt, and improve/optimise current workflows, for example:-  
    - AWS EKS administration of the various Kubernetes clusters, upgrading clusters to newer versions, upgrading the Nginx Ingress Controller, optimising the node and pod resources, creating deployments of applications and cronjobs, optimising the HPA and resources of applications  
    - Jenkins pipeline administration - creation of new pipelines, decommissioning pipelines, optimising current pipelines for better/quick pipeline runs, upgrading Jenkins to the lately version  
    - Administration of our Github Organisation - Creating and removing repo's, user administration, creation and maintenance of Github Actions workflows, implementation and administration of Dependabot  
    - Terraform administration - Upgrading projects from 1.0.6 to 1.4.5, refactoring Terraform HCL code for shared modules and projects, creating and maintaining projects for resources and applications  
    - AWS Administration - IAM policies, creation, maintenance and administration of S3 buckets, API Gateways, VPCs and Transit Gateways, Lambdas, ECR, EC2, Route53, and more  
    - Working from the Jira Service Desk Queue on a weekly rota for issues raised by users, developers, product owners, and Datadog alerts  
    - Datadog administration - Creating log pipelines, creating and updating metrics, monitors, synthetic tests  
    - Documentation library creation and updating to bring documentation to what I call "Delivery Driver Documentation" level - we should be able to grab a delivery driver when dropping something off, sit them in front of the documentation, and they should be able to complete the task  
    - Mentoring and knowledge transfer sessions, building and instilling the DevOps culture and workflows in the team, as well as raising the knowledge levels within the team - the why we do things a certain way, not just the how  

### Kallidus  
**_DevOps Engineer_**  
April 2022 - August 2022  
Remote Working  
  
- Working as a member of the Infrastructure Team in a DevOps capacity  
  
- Migrating the current Infrastructure As Code (IAC) tools (Azure ARM and Powershell) to Terraform  
  
- Creating a new Wiki in Azure DevOps in a Markdown format, creating new documentation, and collating existing information stored in Microsoft OneNote, Product Backlog Items, and Word Documents  
  
- Creating pipelines in Azure DevOps  
  
- Creating a new Postix Email solution, running in Kubernetes, to decomission the 2 Azure Virtual Machines  
  
- Windows Systems Administration  
  
- Azure Kubernetes administration (Editing and deploying a PV.yaml and PVC.yaml to change Persistent Volume's size, Helm chart creation and maintenance, fixing issues in existing deployments/pods)  
  
### Glasswall Solutions  
**_Site Reliability Engineer / DevOps Engineer_**  
June 2020 - April 2022  
Remote Working  
  
- Working as a member of SRE/DevOps Team, providing 24x7 support using Pagerduty for Glasswall products 
  
- Main focus was on the maintenance, uptime, and releases for the Glasswall Email product, an solution built on Azure Kubernetes Service, utilising various resources like Azure SQL, Azure Cache for Redis, Storage Accounts, Traffic Managers, etc.

- Following the Google SRE Guidelines to improve the reliability and performance for our Glasswall Cloud services. 

- Working using a Kanban methodolgy to maximise the effectiveness and transparency of the work carried out, especially within the team (easy to pick up or follow other team members work) 

- Leading a project to take our existing Glasswall Email SaaS product from a shared multi-tenancy service, to be able to create a full deployment of the service for a single client 

	- Previous deployment used Pulumi to create majority of the infrastructure, then manual deployments from the DevOps pipelines of each microservice - Took my manager <2 Weeks to deploy, not including design, planning, conversations, etc.  
  
	- New deployment uses a Python script to deploy the complete base and main infrastructure using Terraform, then automatically deploys the microservices in parallel - New deployment took around 1 hour to complete  

	- Further iteration removed the Python script in favour of an Azure Pipeline Release, utilising a Variable Group to create the TFVars, rather than the person running the deployment manually finding the information, then adding the TFVars file, and running a pull request  

	- We initially had 4 Muli Tenant Production Kubernetes Clusters, 4 Non-Production Kubernetes Clusters, and 3 Single Tenant Production Kubernetes Clusters  

	- After the project we had 4 Multi Tenant Production Kubernetes Clusters, 4 Non-Production Kubernetes Clusters, and <20 Single Tenant Production Kubernetes Clusters  
  
- Full administration of technologies used and supported by the SRE Team, and other teams – Azure, AWS, Datadog, Github, Docker Hub. 

- Standard CI/CD practises of using Git repos with our policies applied to merge all changes using a Pull Request, enabling automated pipelines with Gated Builds, Unit Tests, Smoke Tests, etc 

- Reviewing all code and services before deploying to production using a Blue/Green deployment strategy 

- Always reviewing our processes, playbooks, and technologies to minimise and automate TOIL, maximise our efficiency and continue to demonstrate the company’s culture of excellence 

- Using our P1 incident process, providing timely updates to our Key Stakeholders and Customer Support Team, completing the incident by creating a full post-mortem and participating in a blameless retrospective session to see what went well, and if anything could be improved on 

- Creating and regularly reviewing and updating our Wiki and Documentation with the end goal that we should be able to bring anyone in to be able to follow the guide and complete the task successfully 

 
### Glasswall Solutions  
**_Senior Systems Administrator_**  
May 2019 - June 2020  
4 Springfield Lyons Approach, Chelmsford, Essex, CM2 5LB  

- Working alone and as a member of the IT & Client Support Team, providing product and infrastructure support to both clients and internal users, being part of an out of hours on-call rota. 

- Working in Squads to develop company goals, creating new products, optimising current processes, working on projects with resources from multiple teams. 

- Assisting clients with product set up, creating Office 365 connectors and rules, troubleshooting issues, performing upgrades, providing information on products they use and ways to optimise their current set up. 

- Overhauling the company’s support environment, creating a new support model, implementing new processes (requests and escalations), redesigning the support website and documentation environments. 

- Full administration of technologies required for company use – Office 365, Azure, AWS, Google Suite, Jira, Github, Docker Hub, and Slack. 

- Full AWS Administration – setting up accounts (instances), getting everyone set up with permissions, Multi-Factor Authentication, setting password policies and product restrictions to only products the users needed (Lambda, CloudFront, S3, API Gateway, EC2, ECR). 

- Setting up CloudFront website which connects to a private S3 Bucket, using Lambda for authentication.

- Learning technologies to better support internal users and clients, such as Docker, Kubernetes, React.js, Node.js, Elasticsearch, Redis, Pulumi, Terraform, Juypter Notebooks, Python, Standard Library.

- Automated user on-boarding and off-boarding using a Sharepoint list that triggers a Microsoft Power Automate Flow, which creates the user in all systems and logs a ticket to set up user’s machine and desk. 

- Implementing Multi-Factor Authentication across the company and external clients that use our resources. 

- Working with the Cloud and Core team on issues in their respective SaaS and SDK products. 

- Testing our current products on new technologies (Google Pixelbook, Raspberry Pi 4, STOP OS, Alpine Linux, and more). 

- Using basic Infrastructure tools – Active Directory Users and Computers, Domains and Trusts, DNS, DHCP, Group Policy, etc. 

- Installing and configuring PCs, Laptops, TV Displays using Intel Compute Sticks. 

### DST Systems LTD (formerly IFDS LTD)  
**_Infrastructure Specialist_**  
January 2017 - March 2019  
1 London Road, Brentwood, Essex, CM14 4QP   

- Being a member of the Infrastructure Services team, working on Projects and BAU work, working On-Call 24x7 in a shift pattern, taking part in Quarterly Maintenance and DR Weekends, completing out of hours changes. 

- Utilising Service Now and ITIL processes to manage all BAU work, to create Changes, and pushing them through to completion. 

- Being part of the Exchange focused part of the team to migrate to Exchange 2010, and then further to a hybrid cloud Exchange - Administering and Improving the Exchange environment where possible. 

- Working on the VMware Environments in various sites, building, manging, and maintaining virtual machines. 

- Working with and liaising with various teams on work and projects to improve any areas of the business e.g. working on a Lifecycle project to migrate or decommission 2003 Servers to 2012 R2 and 2016; Working with DBA’s to create a new SQL Server and migrate databases over; Working with the Identity Access Management team to implement a new auditing solution, etc. 

- Increasing and maintaining email security with the Trustwave MailMarshal email filtering system, Symantec Messagelabs, and Symantec Email Encryption (PGP). 

- Using basic Infrastructure tools – Active Directory Users and Computers, Domains and Trusts, DNS, DHCP, Group Policy, etc.  

- Creating and running projects to implement or upgrade various systems and solutions – Solarwinds, Enterprise Vault, ADFS, Certificate Authority, Fire Eye Mandiant, as well as in house applications (Project Slalom, Skylark, AWD, etc). 

### The Travel Corporation

**_Infrastructure Analyst_**  
November 2014 - December 2016  
15 Grosvenor Place, London, SW1X 7HH  

**_Service Desk Engineer_**  
March 2013 - July 2015  
15 Grosvenor Place, London, SW1X 7HH   

- Tasked with a mix of  1st- 3rd Line Support and project work for a variety of systems for over 2000 users, in over 20 sites in EMEA and the Far East.

- Utilising Service Now and ITIL processes to manage all Incidents, Requests, and Change Tasks.

- Answering phone calls from users based in EMEA and the Far East.

- Supporting a wide range of devices including Desktops, Laptops, Servers, Switches, Routers, Tablets, Desk Phones, and Mobile Phones.

- Using VMware to create and manage all our Virtual Machines, upgrading Virtual Hosts, linking branch offices, maintaining Hosts, Clusters, and Storage.

- Using internal Microsoft Administrative tools, including Active Directory, Exchange, Group Policy, DNS, DHCP, etc.

- Creating and maintaining backup schedules using Veeam and Symantec Netbackup in our main office, following up with Crashplan ProE and Symantec Backup Exec for remote sites.

- Installing and supporting Windows and Linux Servers including Server 2008/R2, Server 2012/R2, Ubuntu, CentOS, RedHat, etc.

- Implementing Wireless solutions both singularly and with the Network and Security Team.

- Working on projects including user equipment refreshes, overhauling backup procedures, design and installation of new AVAYA Phone system, and more.

- Working with the digital teams to deploy external Microsoft Office 365 solutions.

- Working with the Development Teams as the point of contact for any DevOps issues, taking over the Development Infrastructure, and assisting in projects to implement new solutions.

- Working away from Head Office at various sites (Bromley, Guernsey, Edinburgh).

- Using various tools to monitor the Systems and Networks of offices around the world – Nagios, Solarwinds, Lansweeper, HP Systems Insight Manager, WSUS, Ninite.

### Conosco LTD

**_Technical Support_**  
December 2012 - February 2013  
The Plaza, 535 King's Road, London, SW10 0SZ  

- My main duties included 1st, 2nd and 3rd line IT and Network Support

- Working and troubleshooting from the Netsuite Case System

- Maintaining a smooth and consistent service for Clients

- Answering and solving support problems and queries, entering Cases into the Case System

- Talking one to one with Clients, troubleshooting the issues they have

- Talking to Service Providers to solve and maintain a smooth service

- RDP to Client’s Servers to troubleshoot and solve issues that have arisen 

### Unanimis Consulting LTD
**_Technical Support Analyst_**  
July 2010 - December 2012  
17 Gresse Street, London, W1T 1QL   

- My main duties included working and troubleshooting from our Zendesk Ticketing System

- Rolling out Microsoft Windows 7 and Microsoft Office 2010 to all 

- Implementing Daily and Weekly checks of the Infrastructure and IT Office Areas 

- Ownership of the Internal Phone System powered by AVAYA

- Ownership of the Mobile Phones powered by Orange

- Rolling out various Programs and Applications including Kaspersky Anti-Virus, AVG Anti-Virus, Microsoft Office 2010, and Mimecast Email Solutions, amongst others

- Schedule Full system backups and recovery using Windows backup, Symantec Backup Exec, and Acronis Backup and Recovery software

- Active Directory AD and Exchange administration


## EDUCATION and IT QUALIFICATIONS  

**_Mayflower High School_**  
September 2005 - June 2016  
A – D grades – Passed all GCSE’s  

## NOTABLE INFORMATION   

**_Work Experience Award_**  
Best work experience feedback in my school year, based on 300 pupils 

**_Duke Of Edinburgh_**  
Gold Award  

## Products Used

**Cloud** – Microsoft Azure, Azure AKS, Amazon AWS, Amazon S3, Amazon CloudFront, Amazon API Gateway, Amazon CodeBuild, Amazon IAM, Microsoft Office 365, Microsoft Sharepoint, Google Cloud Compute 

**IAC** – Terraform and Pulumi 

**CI/CD Pipelines** – Azure DevOps, Github Actions, AWS Cloudformation 

**Languages** – Powershell, Bash, CMD, Python, Node.js, React 

**Operating Systems** – Windows Desktop (XP, Vista, 7, 8, 8.1, 10), Windows Server (2003, 2008, 2016, 2019), Linux (Ubuntu Desktop, Ubuntu Server, Red Hat, CentOS,), Mac OSX 

**Microsoft** - Office (2003, 2007, 2010, 2013, Office for Mac, Office 365), Administrative Tools (Active Directory, Exchange, DHCP, DNS, Print Management, Group Policy) 

**Virtualisation** - VMware ESXi 5.0, 5.1, 5.5, and 6, VSphere (with FT, HA, DRS, sDRS, VMotion, etc) 

**Backup Solutions** – Symantec Netbackup, Symantec BackupExec, Veeam, Crashplan Pro, Windows Backup, Clonezilla, Acronis Backup and Restore 

**Email Security** – Glasswall Filetrust Cloud, Mimecast, Symantec Brightmail, Symantec Messagelabs, Symantec PGP, Trustwave MailMarshal 

**Desktop and Server Security** – Symantec Endpoint Protection, Sophos Endpoint, Kaspersky Anti-Virus For Business, ESET NOD32, AVG For Business, Bitdefender, Malwarebytes, F-Secure 

**Telephony** – Avaya Systems, Software, and Phones, Polycom, Android, iOS, Windows Mobile, Blackberry 

**Networking** – Wireless Solutions, Ruckus, Aerohive, Ubiquiti UniFi, Draytek, Cisco Switches, Juniper Switches 

**Misc** – Datadog, Splunk, Windows Linux Subsystem, Video Editing, Photo Editing, Web Design, Docker, Kubernetes, Github, Jupyter Notebooks, Redis, Pagerduty 
