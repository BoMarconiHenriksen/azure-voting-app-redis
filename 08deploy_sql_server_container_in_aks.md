# Deploy a SQL Server container in Kubernetes with Azure Kubernetes Services (AKS)
https://docs.microsoft.com/lb-lu/sql/linux/tutorial-sql-server-containers-kubernetes?view=sql-server-ver15  
Learn how to configure a SQL Server instance on Kubernetes in Azure Kubernetes Service (AKS), with persistent storage for high availability (HA). The solution provides resiliency. If the SQL Server instance fails, Kubernetes automatically re-creates it in a new pod. Kubernetes also provides resiliency against a node failure.  
### HA solution on Kubernetes running in Azure Kubernetes Service
You can create and manage your SQL Server instances natively in Kubernetes. The example in this article shows how to create a deployment to achieve a high availability configuration similar to a shared disk failover cluster instance. In this configuration, Kubernetes plays the role of the cluster orchestrator. When a SQL Server instance in a container fails, the orchestrator bootstraps another instance of the container that attaches to the same persistent storage.  
![GitHub Logo](https://github.com/BoMarconiHenriksen/azure-voting-app-redis/blob/master/images/kubernetes-sql.png)  
