# Azure vNet with Core Services Simple

<p>This template provisions an Azure vNet with 4 subnets: 
    
    192.168.0.0/26      GatewaySubnet
    192.168.0.64/26     ActiveDirectorySubnet
    192.168.0.128/26    ManagementSubnet
    192.168.0.192/26    DMZSubnet
    
<p></p>
New-AzResourceGroupDeployment -ResourceGroupName Core-Network-WestUS-RG -TemplateFile core-vnet0-westus.json


