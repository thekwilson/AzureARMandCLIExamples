# Azure ARM and Azure CLI Examples
Azure ARM Templates and Azure CLI Script Examples

[VNET-Subnets-NSG-FlowLog Example](VNET-Subnets-NSG-FlowLog-Example.json) - This ARM Template which is based on other examples, Creates A VNet with 2 Subnets (Subnet A & B by default) and then Creates an NSG and attaches that to Subnet A and then turns on [NSG Flow Logs](https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-nsg-flow-logging-azure-resource-manager) for the NSG.  Combining all this into 1 ARM Template and using the necessary nested deployment pattern from [here](https://github.com/Azure/azure-quickstart-templates/blob/master/101-networkwatcher-flowLogs-create/azuredeploy.json) to get the Flow Logs setup correctly is what makes this interesting.
