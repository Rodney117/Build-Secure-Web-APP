
<h1>Build and Secure Web App</h1>

<h2>Description</h2>
This project involved building and securing a custom JavaScript web application on Microsoft Azure. Here's a breakdown of the key functionalities:

Development and Deployment:

Developed a custom JavaScript web application.
Deployed the application within a Docker container hosted on Azure App Service.
Security Implementation:

Key Vault and Certificates:
Created an Azure Key Vault for secure storage of cryptographic keys and certificates.
Generated a self-signed certificate for initial testing (not recommended for production).
Imported and bound a self-signed certificate to the web app for development purposes.
Created and bound an App Service managed certificate for production use (recommended for trust and ease of management).
Azure Front Door:
Created a Front Door instance to act as a global load balancer and improve performance and scalability.
Web Application Firewall (WAF):
Analyzed existing WAF rule sets to understand their functionalities.
Configured custom WAF rules to further enhance application security by filtering malicious traffic.
Azure Security Center:
Analyzed recommendations provided by Azure Security Center to identify potential security vulnerabilities.
Implemented remediation steps based on the security findings to strengthen the overall security posture of the application.<br />


<h2>Languages and Utilities Used</h2>

- <b>Azure Cloud Shell</b> 


<h2>Environments Used </h2>

- <b>Microsoft Azure</b> 

<h2>Project Completion:</h2>

<p align="center">
 <br/>
<img src="https://imgur.com/hF2yaQq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/0tc3xsV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/xphd71h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
