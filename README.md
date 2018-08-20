# Azure Templates

<h3>1. Create 2 Virtual Machines under a Load balancer and configures Load Balancing rules for the VMs</h3>
</br>
<b>Summary</b>
<p>This template allows you to create 2 Virtual Machines under a Load balancer and configure a load balancing rule on Port 80.
</br>
In this template, we use the resource loops capability to create the network interfaces and virtual machines</p>
</br>
<b>Inclusions:</b>
<li>2 x Virtual Machines</li>
<li>2 x Network Interfaces</li>
<li>2 x Storage Accounts</li>
<li>1 x Availability Set</li>
<li>1 x Load Balancer</li>
<li>1 x Gateway</li>
<li>1 x Public IP Address</li>
</br></br>
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcricketaustralia%2FAzure-Templates%2FLoad-Balancer%2Fdeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-2-vms-loadbalancer-lbrules%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
