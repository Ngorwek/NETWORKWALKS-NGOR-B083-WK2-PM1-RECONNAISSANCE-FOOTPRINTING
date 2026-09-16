# NETWORKWALKS-NGOR-B083-WK2-PM1-PENETRATION-TESTING
🛡️ **RECONNAISSANCE &amp; FOOTPRINTING REPORT**

Target: networkwalks.com

Date: September 15, 2026

Author: Intern Pentest Team

Status: Completed

📋 **Executive Summary**

This report documents the initial passive and active reconnaissance phase conducted against networkwalks.com. The objective is to gather domain registration intelligence, map underlying web technologies, resolve network infrastructure, analyze HTTP response behavior, identify Web Application Firewalls (WAFs), and comprehensively enumerate DNS records.

🔍 **Detailed Task Execution & Results**

**Task 1: Domain Registration Details (whois)**

The whois utility was used to query the regional registry for administrative, technical, and registrar information.

**Task 2: Web Technology Fingerprinting (whatweb)**

whatweb was deployed to identify the software, frameworks, and server configurations powering the target web application.

Finding: *WordPress 7.1* and *WordPress Download Manager 3.3.58*

**Task 3: IP Address Resolution (nslookup)**

nslookup queried the default DNS resolver to map the domain name to its corresponding IP address space.

**Task 4: HTTP Response Headers (curl -I)**

curl was utilized to fetch HTTP headers and inspect server configurations, security policies, and redirect behaviors.

**Task 5: WAF Detection (wafw00f)**

wafw00f was run to fingerprint and detect any active Web Application Firewalls protecting the target infrastructure.

**Task 6: DNS Record Enumeration (dnsrecon)**

dnsrecon performed a comprehensive sweep to uncover standard and auxiliary DNS records associated with the domain.

🚀 **Conclusion** 

The reconnaissance phase successfully mapped the target infrastructure. With basic tech profiles, network resolution, and header behaviors defined. Subsequently, Zenmap phases was successfully runs and show one host network.

📝 **Evidences Collected**

<img width="503" height="521" alt="image" src="https://github.com/user-attachments/assets/eb6c0a6e-19ef-410c-810f-45e8d6d402be" />


<img width="869" height="268" alt="image" src="https://github.com/user-attachments/assets/1c21759b-f177-4a1d-a99a-1def9b0e02de" />


<img width="863" height="356" alt="image" src="https://github.com/user-attachments/assets/5e89c781-d815-4fb8-b7ca-e26165602bcd" />


<img width="884" height="317" alt="image" src="https://github.com/user-attachments/assets/0096a6a0-3a9f-4fd1-b78b-62f6efb4855d" />


<img width="873" height="307" alt="image" src="https://github.com/user-attachments/assets/a18802da-b07a-4040-a6ca-da5983001da0" />


<img width="876" height="315" alt="image" src="https://github.com/user-attachments/assets/eebba68f-242f-4306-8426-a3defe3f3b80" />


<img width="577" height="433" alt="image" src="https://github.com/user-attachments/assets/aee91bb2-2d6d-41af-801b-39fae9aff64a" />


<img width="500" height="401" alt="image" src="https://github.com/user-attachments/assets/034d701f-1dd9-4b73-94bf-867ab7de0851" />


<img width="499" height="401" alt="image" src="https://github.com/user-attachments/assets/b1fdb8a1-dd3e-45df-920a-d453a7a3b63f" />









