# Tshirt sizing by environment input

This example show how to write Bicep modules to accept an input for a type of environment. For example `test` or `production`.
Based on the input the storage account will be configured according to the specification set in the modules `environmentSettings` object.

to deploy run `new-azdeployment -TemplateFile .\tshirt\main.bicep -Location westeurope -Name test -environment prod`