# Internal Load Balancer

New-AzureRmResourceGroupDeployment -Name ILB-RG -ResourceGroupName popenshift `
    -TemplateFile 'C:\Users\H224236\Documents\GitHub\internal-load-balancer\azuredeploy.json' `
    -TemplateParameterFile 'C:\Users\H224236\Documents\GitHub\internal-load-balancer\azuredeploy.parameters.json'