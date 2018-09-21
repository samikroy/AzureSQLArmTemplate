# AzureSQLArmTemplate
ARM template created to provision Azure SQL database for demo purpose.
Source Link
https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-template-deploy
Powershell
New-AzureRmResourceGroupDeployment -Name "DemoDeployment" -ResourceGroupName <Resource Group Name> -TemplateFile "<Template file path>" -TemplateParameterFile "<Template paramater file path>"
