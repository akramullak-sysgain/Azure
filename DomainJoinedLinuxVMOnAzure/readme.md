This example demonstrates how to create domain joined Linux VMs on Azure using Azure AD Domain Service. 

* azuredeploy.json deploys a single linux VM that is domain joined and Kerberos enabled
* azuredeploy_multivm.json deploys a set of VMs that are domain joined and Kerberos enabled
* once you have a set of VMs, you can follow the instructions in setupcloudera folder to set up a domain joined Kerberos enabled cloudera cluster 

Note that you can create a small instance single VM, but if you want to set up a Cloudera cluster, provision at least 4 Standard_DS13 VMs.  Cloudera may not run on smaller VMs. 