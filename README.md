<h1> MicroSoft Azure SOC and SIEM </h1>

<h2>Description</h2>

In this project, I am constructing a honeynet within Azure to replicate real-world cyber-attacks, with a strong focus on Azure Security, Incident Response, and environment hardening. The main objective is to establish intentionally vulnerable virtual machines on Azure, designed to attract potential threat actors. Through this honeynet, I will comprehensively analyze the attack techniques employed by adversaries.To monitor and scrutinize the attacks effectively, I will utilize Microsoft Sentinel, an advanced Security Information and Event Management (SIEM) solution. By leveraging Sentinel, I will build an attack map and configure alerts based on the gathered data, enabling the identification and classification of potential security incidents. Once incidents are identified, I will initiate a prompt response to address them, while simultaneously investigating and remediating the vulnerabilities exploited by attackers. For this purpose, I will employ the best practices outlined in NIST SP 800-61 and follow Azure's recommended security measures.

<br/>
<img src="https://github.com/haddasah708/haddasah708/blob/main/Azure%20SOC%20SIEM%20Diagram%20(1).png" height = 80% alt="Azure SOC and SIEM Image"/>
<br />
Upon implementing the necessary improvements and mitigating vulnerabilities, I will conduct a comprehensive assessment of the environment, comparing the results before and after the hardening measures. This evaluation will allow for a thorough examination of the effectiveness of the applied security measures, providing valuable insights into the enhanced resilience of the system. By executing this project, I aim to gain a deep understanding of attacker techniques, enhance incident response capabilities, and bolster the overall security posture of the Azure environment by implementing industry best practices and employing cutting-edge security tools."

<br />


<h2>Languages and Utilities Used</h2>

- <b>KQL</b>
- <b>SQL Server Management Studio </b>

<h2>Environments Used </h2>

- <b>Azure</b>

<h2>Program walk-through:</h2>

<h3>Section 1 : Azure Lab Structure(HoneyNet) </h3>

- <b>Created one Azure Subscription using 30-day free trial.</b>
- <b>Created a Resource Group to hold all resources and Virtual Network(VNets) to manage networking of resources.</b>
- <b>Created three Virtual Machines; a windows-vm, a linux-vm and an attack-vm. </b>
- <b>Configured Network Security Groups (Inbound Security Rules)for Linux and Windows Virtual machines to allow all Inbound Traffic.</b>
  
</b>Windows-VM Network Security Group(Port Rules)</b>
<img src="https://github.com/haddasah708/haddasah708/blob/main/Screenshot%202023-07-15%20142213.png" height = 40% alt="Azure SOC and SIEM Image"/>
<br />
  
</b>Linux-VM Network Security Group(Port Rules) </b>
<img src="https://github.com/haddasah708/haddasah708/blob/main/Screenshot%202023-07-15%20142258.png " height = 80% alt = "Azure SOC and SIEM Image"/>

<h3>Section 2 : Logging and Monitoring </h3>

- <b>Created Log Analytics Workspace and Setup/Connect Sentinel </b>
- <b>Created an Azure Storage Account, a container within Account and uploading Geo-Data files. [Waiting for Data to load]</b>


