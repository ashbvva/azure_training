# azure_training

http://microsoftazurepass.com
https://portal.azure.com/#home
https://github.com/Azure-Samples/batch-python-quickstart


CLI
az login
az group create --name aruAKSCluster --location eastus
az aks create --resource-group aruAKSCluster --name aruAKSCluster --node-count 1 --enable-addons monitoring --generate-ssh-keys

kubectl get nodes
kubectl apply -f azure-vote.yaml
kubectl get service azure-vote-front --watch
