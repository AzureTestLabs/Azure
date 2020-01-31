# Shared Services Hub - Resource Groups

Resource Groups for Shared services Hub & Spoke Network

<p>Core-Network-WestUS-RG
<p>Core-ADDS-WestUS-RG
<p>Core-Management-WestUS-RG
<p>Core-DMZ-WestUS-RG


New-AzDeployment `
  -Name coreResourceGroupDeployment `
  -Location westus `
  -TemplateUri https://raw.githubusercontent.com/AzureTestLabs/Azure/master/Subscription/ResourceGroups/Core-Services-RG/azuredeploy.json 


