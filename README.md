# Create a Virtual Machine from an image

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmikebranstein%2Fazure-identity-workshop-vm%2Fmaster%2F1%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmikebranstein%2Fazure-identity-workshop-vm%2Fmaster%2F1%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

> Prerequisite - The generalized image VHD should exist, as well as a Storage Account for boot diagnostics

This template allows you to create a Virtual Machine from an unmanaged User image vhd. This template also deploys a Virtual Network, Public IP addresses and a Network Interface.