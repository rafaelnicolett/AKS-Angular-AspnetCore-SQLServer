# AKS-Angular-AspnetCore-SQLServer
Azure Kubernetes Service (AKS) Sample Application developed in Angular, ASP.net Core and SQL Server

Azure Kubernetes Service(AKS) makes it simple to deploy a managed Kubernetes cluster in Azure. The scope of this blog is to show how easy it is to deploy a sample application to AKS which is developed in Angular, ASP.net core and SQL Server on Linux. 

The components and steps needed to deploy these to AKS are
• SQL Server on Linux
  ◦ Create deployment for SQL Server on Linux
  ◦ Deploy to AKS
• ASP.net Core Web API
  ◦ Create ASP.net Core Web API
  ◦ Create a docker image
  ◦ Publish docker image to Docker Hub
  ◦ Create deployment for Web API
  ◦ Deploy to AKS
• Angular App
  ◦ Create and Angular App
  ◦ Create a docker image
  ◦ Publish docker image to Docker Hub
  ◦ Deploy to AKS

You can read in detail by going through this article https://blogs.msdn.microsoft.com/atverma/2018/09/16/azure-kubernetes-service-aks-deploying-angular-asp-net-core-and-sql-server-on-linux/

# Multiple ways to load App configuration in ASP.net Core Web API

Hosting Environment specific appsettings.json
Dockerfile Environment Variables
Kubernetes
Container Environment variables with data from ConfigMap/Secret
Populate Volume (Config file) with data stored in a ConfigMap/Secret
Azure Key Vault Secrets

You can read in detail by going through this article 
https://blogs.msdn.microsoft.com/atverma/2018/10/19/asp-net-core-2-1-web-api-load-app-configuration-from-appsettings-json-dockerfile-environment-variables-azure-key-vault-secrets-and-kubernetes-configmaps-secrets/
