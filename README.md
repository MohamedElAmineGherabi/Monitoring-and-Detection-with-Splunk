<h1>Monitoring and Detection with Splunk (SIEM)</h1>


<h2>Project Details</h2>
Splunk (one of the most popular security information and event management (SIEM) platforms in the world) is a powerful tool used by cybersecurity professionals to monitor, search, and analyze machine-generated big data via a web-style interface. This lab focuses on understanding how to use Splunk for effective monitoring and detection of potential security threats.<br />
<br />

**Tasks Breakdown:**

**Task 1: Getting Started in the Lab Environment**

Started by initializing the lab environment which involved setting up the Splunk infrastructure. This foundational step is essential as it ensures all data ingestion and analysis can be performed efficiently.

**Task 2: Uploading Data to Splunk**

Learned how to upload various types of data to Splunk. This is crucial for ensuring that the data needed for analysis is correctly integrated into the system.

**Task 3: Performing Searches in Splunk**

Conducted searches within Splunk to locate specific information. Mastering search commands and understanding the syntax is vital for effective data analysis and threat detection.

**Task 4: Creating and Sharing Reports in Splunk**

Focused on creating and sharing reports. This involves summarizing findings and sharing insights with relevant stakeholders, which is critical for proactive threat management and response.

**Task 5: Creating Dashboards in Splunk**

Developed dashboards for continuous monitoring. Dashboards are essential for visualizing key metrics and real-time data to quickly assess and respond to threats.

**Bonus Task: Running a Customized Scan on a Target**

This is an additional task that I wanted to add where I will be running a customized scan on a target and saving the results in a txt file for the Security Team to review in the next meeting. I will:<br />


- Perform an Nmap scan, scanning ports 22-80, on the target: scanme.nmap.org.

- Use the appropriate option to enable OS and version detection, script scanning, and traceroute.

- Set my scan to -T3 for the timing execution of the scan.

- Output the scan results to a txt file named: output.txt.

- Verify the contents of the output.txt file.

- Be sure to reference my Nmap man page for help.

<br />

**Key Takeaways:**

This lab enhanced my technical skills in using Splunk for real-time monitoring, detecting potential malicious activities, and complex data analysis. It also provided practical experience in managing and interpreting large datasets, which is crucial for effective cybersecurity defense strategies. The ability to customize and utilize Splunk's powerful searching and reporting tools prepares me for advanced cybersecurity monitoring and detection tasks.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Splunk Interface: Utilized for all data ingestion, searches, report generation, and dashboard creations.</b> 
  

<h2>Environments Used </h2>

- <b>Splunk Environment: Conducted the project within Splunk’s own operational environment, which is optimized for data analysis and monitoring tasks. This setup is essential for handling large-scale data specific to cybersecurity needs.

</b>

<h2>Program walk-through:</h2>

In this lab, I will be acting as a security analyst that is using Splunk to review log data related to the company's web application (buttercupgames). The first step will be to connect to the Splunk server and upload the data for analysis (Task 1 & 2).

<p align="center">
Task 1: Getting Started in the Lab Environment <br/>
<br />
<img src="https://i.imgur.com/H5SRk79.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/NhDzAoW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
Task 2: Uploading Data to Splunk  <br/>
<br />
<img src="https://i.imgur.com/nTnUCVt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/c7iQqw0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/6dQg9mt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/z6IzyhB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/oZBXXUD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/PBPpscw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/c2oBNko.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



<br />
<br />
Task 3: Performing Searches in Splunk <br/>
<br />
<img src="https://i.imgur.com/6OW2UcB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/ASgTmRP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/g4nxkky.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
Task 4: Creating and Sharing Reports in Splunk  <br/>
<br />
<img src="https://i.imgur.com/tYk26xA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/X79E6Ow.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/IRVYs6l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/PxM07VK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/zSPeYY3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/GNNDreq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<br />
<br />
Task 5: Creating Dashboards in Splunk  <br/>
<br />
<img src="https://i.imgur.com/KWhztEN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/UkPQL5C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/mawiIpb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/ZHlRb1p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/uT6LkZE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/bRmG8ni.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/wj47Z1q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/An7vlYj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/ewO3tx9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>








<br />
<br />
Bonus Task: Running a Customized Scan on a Target
<br/>
<br/>
<img src="https://i.imgur.com/UftArVE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<img src="https://i.imgur.com/bVmjmPE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<img src="https://i.imgur.com/sa917y7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<img src="https://i.imgur.com/vOvMqKJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<img src="https://i.imgur.com/jgo7hzD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
