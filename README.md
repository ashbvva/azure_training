# azure_training

http://microsoftazurepass.com
https://portal.azure.com/#home
https://github.com/Azure-Samples/batch-python-quickstart


CLI
az login <br/>
az group create --name aruAKSCluster --location eastus <br/>
az aks create --resource-group aruAKSCluster --name aruAKSCluster --node-count 1 --enable-addons monitoring --generate-ssh-keys<br/>

kubectl get nodes<br/>
kubectl apply -f azure-vote.yaml<br/>
kubectl get service azure-vote-front --watch<br/>

az webapp show --resource-group aru-appservice-rg --name aru-appservice --query possibleOutboundIpAddresses --output tsv<br/>

https://docs.microsoft.com/en-us/learn/browse/?products=azure&roles=developer&resource_type=learning%20path


================================================================================================================

## [AZ-203](https://www.microsoft.com/en-us/learning/exam-az-203.aspx)

### Virtual Machines
    https://azure.microsoft.com/en-us/services/virtual-machines/
### Azure Batch Services
    https://docs.microsoft.com/en-us/azure/batch/
    
### Azure Kubernetes Service (AKS)
    https://docs.microsoft.com/en-us/azure/aks/
#### Docker
    https://docs.docker.com/get-started/ 
    
###### Enable : Microsoft-Hyper-V 
```powershell
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
```
###### Docker Community Edition : Edge Releases of 2018

Click here : [Docker CE Edge Releases 2018](https://download.docker.com/win/edge/28777/Docker%20for%20Windows%20Installer.exe).

##### Kubernetes (k8s)
    https://kubernetes.io/docs/tutorials/
    
### App Service
    https://docs.microsoft.com/en-us/azure/app-service/
    
### Azure Functions
    https://azure.microsoft.com/en-us/services/functions/
### Traffic Manager
    https://docs.microsoft.com/en-us/azure/traffic-manager/
### API Management
    https://docs.microsoft.com/en-us/azure/api-management/
### Azure Search
    https://docs.microsoft.com/en-us/azure/search/search-what-is-azure-search
### Azure Storage
    https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction
### Azure Functions
    https://docs.microsoft.com/en-us/azure/azure-functions/
### Azure CDN
    https://docs.microsoft.com/en-in/azure/cdn/
