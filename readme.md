az group create --name samres3 --location eastus
> az group deployment create --name "samres3" --resource-group samres3 --template-file "./storage-account.json"

#az deployment group create --name "samres3" --resource-group samres3 --template-uri "https://raw.githubusercontent.com/samzri1/test-arm-azure/master/azuredeploy.json"

> az group delete --name samres3 -y


