# Shared Services Hub - Resource Groups

Resource Groups for Shared services Hub & Spoke Network

<p>Core-Network-<location>-RG
<p>Core-ADDS-<location>-RG
<p>Core-Management-<location>-RG
<p>Core-DMZ-<location>-RG
<p>Core-LogAnalytics-<location>-RG

Download and deploy these templates with PowerShell

New-AzDeployment `
-Name coreResourceGroupDeploymentEast `
-Location eastus `
-TemplateFile core-resourcegroups-eastus.json

New-AzDeployment `
-Name coreResourceGroupDeploymentWest `
-Location westus `
-TemplateFile core-resourcegroups-westus.json

Deploy these templates directly with CloudShell

New-AzDeployment `
-Name coreResourceGroupDeploymentWest `
-Location westus `
-TemplateUri https://raw.githubusercontent.com/AzureTestLabs/Azure/master/Subscription/ResourceGroups/Core-Services-RG/core-resourcegroups-westus.json


New-AzDeployment `
-Name coreResourceGroupDeploymentWest `
-Location westus `
-TemplateUri https://raw.githubusercontent.com/AzureTestLabs/Azure/master/Subscription/ResourceGroups/Core-Services-RG/core-resourcegroups-eastus.json
