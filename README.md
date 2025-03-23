<h1>Vulnerability Management Lab (Tenable and Azure)</h1>

<h2>Overview</h2>
This lab demonstrates the fundamentals of vulnerability management using Tenable’s vulnerability scanning tools in a Azure environment.


<h3>Tasks performed</h3>

- <b>Successfully designed and implemented a hands-on vulnerability management lab environment utilizing Tenable (cloud-based platform) and Microsoft Azure.</b>
  
- <b>Created and configured a Windows 10 virtual machine in Azure to serve as the target for vulnerability scanning.</b>
  
- <b>Utilized Tenable to perform comprehensive vulnerability scans, identifying outdated software, misconfigurations, and compliance violations (DISA STIGs).</b>
  
- <b>Analyzed scan results to understand the nature and severity of identified vulnerabilities, utilizing resources like ChatGPT and STIG Viewer/Event Sentry for deeper insights.</b>
  
- <b>Demonstrated practical experience in vulnerability remediation by addressing identified issues, including uninstalling vulnerable software and modifying system configurations.</b>

- <b>Conducted multiple scan cycles to verify the effectiveness of remediation efforts and track the improvement in the security posture of the virtual machine.</b>

- <b>Gained practical experience with industry-standard vulnerability management tools and processes, enhancing skills relevant to cybersecurity analyst and related roles.</b>

<h2>Environments Used</h2>

- Azure for VM setup
- Tenable Online Vulnerability Management Tool
 
<h2>Walk-Through</h2>

<p align="center">

Created a Windows 10 Pro VM in Azure <br/>
<img src="https://i.imgur.com/sZMJEpi.png" height="80%" width="80%" alt=""/> 
<br />
<br />
Disabled VM firewall to give access to the Tenable tool<br/>
<img src="https://i.imgur.com/da54fbT.png" height="80%" width="80%" alt=""/> 
<br />
<br />
Created a vulnerability scan configuration to check for STIG compliance <br/>
<img src="https://i.imgur.com/joiTcvY.png" height="80%" width="80%" alt=""/>
<br />
Windows 10 STIG compliance <br/>
<img src="https://i.imgur.com/V2q3ys7.png" height="80%" width="80%" alt=""/>
<br />
<br />
<br />
Tenable scan results <br/>
<img src="https://i.imgur.com/tTrBbx7.png" height="80%" width="80%" alt=""/>
<br />
<br />
Creating simulate vulnerabilities (enabling guest account on vm and downloading an old Firebox browser)<br/>
<img src="https://i.imgur.com/6QA5W4T.png" height="80%" width="80%" alt=""/>
<br />
<img src="https://i.imgur.com/cp6TaxN.png" height="80%" width="80%" alt=""/>
<br />
<br />
Using websites like STIG Viewer/Event Sentry to help with remediation<br/>
<img src="https://i.imgur.com/uf4ujTx.png" height="80%" width="80%" alt=""/>
<br />
<br />
Remediate the simulate vulnerabilities<br/>
- Unistalled Firefox
- Disabled Guest Account
<br />
<br />
</p>

