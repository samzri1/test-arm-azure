az group create --name testgrp --location eastus
> az group deployment create --name "testarm" --resource-group testgrps --template-file "./storage-account.json"
> az group delete --name acgarmcourse -y