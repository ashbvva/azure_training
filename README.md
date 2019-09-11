# azure_training

http://microsoftazurepass.com
https://portal.azure.com/#home
https://github.com/Azure-Samples/batch-python-quickstart


CLI
az login<\br>
az group create --name aruAKSCluster --location eastus<\br>
az aks create --resource-group aruAKSCluster --name aruAKSCluster --node-count 1 --enable-addons monitoring --generate-ssh-keys<\br>

kubectl get nodes<\br>
kubectl apply -f azure-vote.yaml<\br>
kubectl get service azure-vote-front --watch<\br>

az webapp show --resource-group aru-appservice-rg --name aru-appservice --query possibleOutboundIpAddresses --output tsv<\br>
