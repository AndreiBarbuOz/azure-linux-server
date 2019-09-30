# azure-linux-server
Linux server in Azure, hosting a range of services


## Deployment

```
az group deployment create --resource-group presales-cloud-poc-rg --template-file .\azure-deploy-server.template.json --mode Complete --name linuxServer --parameters sshKey=@id_rsa.pub
```