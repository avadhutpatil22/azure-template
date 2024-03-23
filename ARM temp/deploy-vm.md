#create resouce group if it does not exits
az group create --name vscode --location 'Central India'

##create virtual machine

az deployment group create --resource-group vscode --template-file file name
