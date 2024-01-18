<b>Deploy Metapsloitable and Scan the target using Nessus </b></br>

<b>Introduction</b></br>
In the realm of cybersecurity, staying ahead of potential vulnerabilities is crucial. One effective tool for vulnerability management is Nessus, a comprehensive solution that helps identify and remediate security weaknesses. With Nessus, you can gain full visibility into your network by conducting a vulnerability assessment. In this mini project,you will go through the five steps for Nessus scan and generate the report

<b>Install Nessus</b></br>

Here I configured Credentials for a basic scan on a windows machine. This allows credentialed scans to run, which can provide much more complete results and a more thorough evaluation of the vulnerabilities in your environment. 
![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/24eabcb4-a7ba-448d-b48c-5558494dc4ff)


<b>Deploy Metapsloitable (deliberate vulnerabile machine, will act as a target)</b></br>
Here I deployed Metapsloitable(windows machine) in Microsoft Azure in the location US east which would be our target machine. The public ip address of windows device 3.136.17.100 is used as a target machine ip address for scanning using Nessus.

![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/69449ed6-1bcd-44d8-ba2b-8658e960a002)

<b>Scan the target using Nessus</b></br>
Viewing scan results can help you understand your organization’s security posture and vulnerabilities. Color-coded indicators and customizable viewing options allow you to tailor how you view your scan’s data.
Upon scanning the public ip address 3.136.17.100 vulnerabilities are scanned and results are generated based on which we can categorize critical,high,medium,low,info based vulnerabilities and analyse the result
![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/ba780c5e-01af-4d04-bca1-76fed1711b14)

![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/6a37b716-583c-4527-95ef-edf11b2a611f)


<b>Generate the Report:</b></br>
Scan results can be exported in several file formats. Some of these report formats are customizable, while others are designed to be imported into another application or product, such as Pdf,Microsoft Excel or Tenable.sc. To Export a Scan Report:

a.Start from a scan's results page
b.In the upper-right corner, click Export.
c.From the drop-down box, select the format in which you want to export the scan results.
d.Click Export to download the report.

The reports we downloaded here is Detailed vulnerabilities by host .

![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/7f4dd133-a80a-459b-b12d-0290345558d6)

<b>Analayze Reports</b></br>

Here reports are analyzed based on which we can list the identified vulnerabilities, sorted by severity.

![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/c7f0e9fc-c5c0-48cc-bd24-2d8b1ca5f27b)
![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/03ba64f3-bf9b-45d0-a983-f34f1d82aded)

<b>Conclusion:</b></br>
In this mini project, I had the opportunity to explore Nessus vulnerability management by deploying Metapsloitable  (windows machine) in Microsoft Azure as our target vulnerable machine.Upon scanning the public ip address vulnerabilities are scanned and results are generated and downloaded using pdf report.In a normal SOC environment, you wouldn't normally have the Security Analyst who is running the vulnarability scan also do the remediations, due to seperation of duties, instead they would normally present this information to the respective subject matter expert Through this hands-on experience, I gained valuable insights into the power and effectiveness of Nessus in mitigating potential security risks.

