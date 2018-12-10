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
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcricketaustralia%2FAzure-Templates%2Fmaster%2FLoad-Balancer%2Fdeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fcricketaustralia%2FAzure-Templates%2FLoad-Balancer%2Fdeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
<hr>
</br>
<h3>2. Create Auto Scale Virtual Machines under a Load balancer and configures Load Balancing rules for the VMs</h3>
</br>
<b>Summary</b>
<p>The following template deploys a Virtual Machine ScaleSet + Autoscale Setting for Virtual Machine ScaleSet plan based on a single metric.

If the metric is above the upper threshold, the example autoscale setting will scale out the instance count. If the metric is below the lower threshold, the example autoscale setting will scale in the instance count. This sample illustrates how easy it is to automate autoscale setting configuration for Virtual Machine ScaleSets via templates.</p>
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
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcricketaustralia%2FAzure-Templates%2Fmaster%2FLoad-Balancer%2Fdeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fcricketaustralia%2FAzure-Templates%2Fmaster%2FLoad-Balancer%2Fdeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
