# IntegratorCore

------------------------------------------------------------------------------------------------

#### Comandos para subida da imagem (HML)

##### Tag da imagem
###### docker tag integratornet:v1 brmallsk8s.azurecr.io/msintegracao/brmalls-ms-loader-sibel:v1

##### Login na azure
###### az acr login --name brmallsk8s

##### Alterando ambiente do AKS
###### az aks get-credentials --resource-group BRMALLS_MS_PRD --name k8s-prd-ms

##### Push para ACS (Azure repository)
###### docker push brmallsk8s.azurecr.io/msintegracao/brmalls-ms-loader-sibel:v1

#### Comandos para subida do projeto no AKS

##### Comando para subida de deployment kubernetes
###### kubectl create -f ./kubernetes/api-deployment.yml

------------------------------------------------------------------------------------------------