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
