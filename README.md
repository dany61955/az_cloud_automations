# az_cloud_automations


Az login power shell

Make sure to replace the placeholder values (<your-client-id>, <your-client-secret>, <your-tenant-id>, <your-subscription-id>, <your-resource-group-name>, <your-bastion-name>, <your-vm-name>, <your-vnet-name>, <your-subnet-name>, <your-bastion-ip>) with your actual Azure details.

This script first installs the Azure PowerShell module if it's not already installed, then imports the module and prompts for your Azure Service Principal credentials. After successful authentication, it proceeds to create the bastion tunnel using the az network bastion create command. Finally, it displays a success message.




