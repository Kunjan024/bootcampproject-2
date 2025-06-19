Project 2

Create a multi enviroment(production/staging/development) Infrastructer deployment with CICD  

IOC:: Terraform
CICD:: cloud build / github actions 
Services:: storage/sql/gke/metrics dashboard 

orderservice-dev || dev be url || ui-dev
orderservice-prd || prd be url || ui-prd 

dev : (UI => BE => DB)

stg : (UI => BE=> DB) 

beta : (UI => BE=> DB) 

prd : (UI => BE => DB)
