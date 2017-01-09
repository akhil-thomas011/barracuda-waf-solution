# Barracuda WAF on Azure 
## Solution Overview 
This Azure Quick Start template deploys a Barracuda Web Application Firewall Solution on Azure.  The Solution includes Barracuda WAF Appliance and backend web servers running Windows Server 2012 R2 with IIS. Template will build everything starting from Azure Infrastructure components to Barracuda deployment and Windows VM deployment with automated IIS Web Server installation. This template will deploy one Barracuda WAF VM and multiple backend web servers as per requirement. 

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSpektraSystems%2Fbarracuda-waf-solution%2Fmaster%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FSpektraSystems%2Fbarracuda-waf-solution%2Fmaster%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a> 

The Barracuda Web Application Firewall inspects inbound web traffic and blocks SQL injections, Cross-Site Scripting, malware uploads & application DDoS and other attacks targeted at your web applications. It also inspects the responses from the back-end web servers for Data Loss Prevention (DLP). The integrated access control engine enables administrators to create granular access control policies for Authentication, Authorization & Accounting (AAA), which gives organizations strong authentication and user control. The onboard L4/L7 Load Balancing capabilities enable organizations to quickly add back-end servers to scale deployments. Application acceleration capabilities including SSL Offloading, caching, compression, and connection pooling, ensure faster application delivery of web application content. 

Once deployment finishes, you will able to directly access fully configured Barracuda GUI and start publishing your web applications.


