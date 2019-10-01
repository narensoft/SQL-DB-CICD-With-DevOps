# Azure SQL Database CI/CD with Azure DevOps

### Business Problem:

Azure DevOps provides developer services to support teams to plan work, collaborate on code development, and build and deploy applications. Developers can work in the cloud using Azure DevOps Services or on-premises using Azure DevOps Server, formerly named Visual Studio Team Foundation Server (TFS). Azure DevOps provides an integrated set of features that you can access through your web browser or IDE client. You can use one or more of the following services based on your business needs:

* **Azure Repos** provides Git repositories or Team Foundation Version Control (TFVC) for source control of your code
* **Azure Pipelines** provides build and release services to support continuous integration and delivery of your apps
* **Azure Boards** delivers a suite of Agile tools to support planning and tracking work, code defects, and issues using Kanban and Scrum methods
* **Azure Test Plans** provides several tools to test your apps, including manual/exploratory testing and continuous testing
* **Azure Artifacts** allows teams to share Maven, npm, and NuGet packages from public and private sources and integrate package sharing into your CI/CD pipelines
* Collaboration tools that include customizable team dashboards with configurable widgets to share information, progress and trends; built-in wikis for sharing information; configurable notifications and more.

I have observed that many developers who are developing their applications. use CI/CD with Azure DevOps for deployment of the code very efficiently and effectively but when we talk about the CI/CD for Databases schema deployment using Azure DevOps many developers are not much aware of how to do this or where can they start?  How can they use build and release pipelines to deploy our database project?

### Solution:
A build pipeline defines the steps to take during build and the triggers that initiate a build.  A release pipeline can be used to automate database deployments to one or more environments.  Approvers can be added to guarantee that releases occur at the right time in the project schedule.  Of course, logging of both types of pipelines allows the support staff to easily debug any issues that arise.  Finally, releases can be initiated manually or automatically off a build. Let’s take a scenario where your boss has asked you to investigate how to manage continuous deployments using Azure DevOps for Azure SQL Database deployment.  I will show you with the series of articles how can you configure Continuous Integration and Continuous Deployment of Azure SQL Database using Azure DevOps and Visual Studio.

I have created a series of 5 Parts as follows in PDF format:
1. [Create Azure SQL Database for CI/CD Project](https://github.com/narensoft/SQL-DB-CICD-With-DevOps/blob/master/01-SQL_DB_Creation_for_CICD.pdf)
2.	[Create a DevOps Project and Database Project in VS](https://github.com/narensoft/SQL-DB-CICD-With-DevOps/blob/master/02-SQL_DB_Project_Crateion_for_CICD.pdf)
3.	[Develop Build Pipeline in Azure DevOps](https://github.com/narensoft/SQL-DB-CICD-With-DevOps/blob/master/03-SQL_DB_Project_Build_for_CICD.pdf)
4.	[Develop Release Pipeline in Azure DevOps](https://github.com/narensoft/SQL-DB-CICD-With-DevOps/blob/master/04-SQL_DB_Project_Release_for_CICD.pdf)
5.	[Test Azure SQL Database CI/CD with Azure DevOps](https://github.com/narensoft/SQL-DB-CICD-With-DevOps/blob/master/05-SQL_DB_Project_TableAddModify_CICD.pdf)

### Pre-requisites:
* Visual Studio 2019/2017
* Active Azure Subscription

##### Happy Learning!
