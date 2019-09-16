# networktraining - deploy VMs

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdalejmarshall%2Fnetworktraining%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template will deploy 3 Virtual Machines, one in each subnet you have created
- 2 x WebVM
- AppVM
- DataVM

The WebVM will have a publicIP attached and Apache Web Server installed. You can use the Public IP to confirm the VM and the web server are up and running.