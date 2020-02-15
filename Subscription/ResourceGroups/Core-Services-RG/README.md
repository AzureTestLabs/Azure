# Shared Services Hub - Resource Groups

Resource Groups for Shared services Hub & Spoke Network

<p>Core-Network-<location>-RG
<p>Core-ADDS-<location>-RG
<p>Core-Management-<location>-RG
<p>Core-DMZ-<location>-RG
<p>Core-LogAnalytics-<location>-RG



New-AzDeployment `
-Name coreResourceGroupDeploymentEast `
-Location eastus `
-TemplateFile core-resourcegroups-eastus.json

New-AzDeployment `
-Name coreResourceGroupDeploymentWest `
-Location westus `
-TemplateFile core-resourcegroups-westus.json

