New-AzResourceGroupDeployment -ResourceGroupName Core-ADDS-WestUS-RG -TemplateFile azuredeploy.json -templateparameterfile NS3.parameters.json

New-AzResourceGroupDeployment -ResourceGroupName Core-ADDS-EastUS-RG -TemplateFile azuredeploy.json -templateparameterfile NS4.parameters.json