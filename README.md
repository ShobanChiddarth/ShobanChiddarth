## Introduction

I am a GNU+Linux user with a profound interest in Cybersecurity and Cloud Computing. As I have been getting into computers deeper and deeper I got interested in protecting systems. I am currently in the final year of my college and open to do internships in Cybersecurity.


## Skills and Tools

- **Security Operations**: Wazuh SIEM, threat detection, FIM, alert triage
- **Detection Engineering**: SigmaHQ rule authoring, OpenSearch, log analysis
- **Network Engineering**: TCP/IP, DNS, VPC Design, Subnetting, Routing, Virtual Networking, Cisco IOS
- **Network Security**: pfSense, Pi-hole, Wireshark, configuring and securing network devices
- **Cloud Platforms**: AWS
- **Cloud Security**: AWS IAM, Security Groups, NACLs, CloudTrail, S3 bucket policies
- **Infrastructure as Code**: Terraform
- **CI/CD & Automation**: GitHub Actions, systemd
- **Programming**: Python (FastAPI, scripting, automation), Bash
- **Containers & Virtualization**: Docker, VirtualBox
- **Operating Systems**: Linux (daily driver, server administration, VPS hardening), Windows
- **Version Control**: Git, GitHub


## Labs

| Title | Description |
|--- | ---|
| [Physical Network Engineering Home Lab](https://shobanchiddarth.hashnode.dev/series/network-engineering-home-lab) | D |
| [Wazuh SIEM Lab](https://github.com/ShobanChiddarth/siem-home-lab-wazuh) | SIEM Home Lab using Wazuh with Multi-Platform Log Ingestion and Attack Simulation |
| [ettercap MITM Lab](https://github.com/ShobanChiddarth/ettercap-mitm-home-lab) | ARP Poisoning MITM Lab using ettercap and traffic analysis with Wireshark |
| [Cisco Packet Tracer CCNA Learning Labs (from jeremy's course)](https://github.com/ShobanChiddarth/Jeremy-Labs-CCNA-Prep) | It has all the labs I practiced for CCNA. See the README of that repo. |
| [Superior VM Intercommunication](https://shobanchiddarth.hashnode.dev/the-superior-way-to-make-vms-communicate-with-each-other-as-well-as-host-with-internet-access-42m1) | Template for most of my Virtual labs |


## My Projects

| Title | Description |
|---|---|
| [SigmaDojo](https://github.com/ShobanChiddarth/SigmaDojo) | <span><ul><li>Created TryHackMe style labs to teach Detection Engineering (sigma rule writing) to users</li><li>Added a custom rule interpreter to query synthetic log datasets</li><li>Added optional export to Splunk SPL or Sentinel KQL syntax</li></ul></span> |
| [ResumeOps](https://github.com/ShobanChiddarth/ResumeOps) | <span><ul><li>CI/CD for your Resume</li><li>Lets you maintain several versions of your Resume in plain text files so you can version control them in Git</li><li>Implements GitOps to automatically convert to .pdf files</li><li>Saves time spent in manually exporting and managing Resumes</li></ul></span> |
| [telegram-proxy-server-aws](https://github.com/ShobanChiddarth/telegram-proxy-server-aws) | <span><ul><li>Created a MTProto Proxy server for Telegram in AWS</li><li>Encrypted and obfuscated a connection from Telegram clients to Telegram over the proxy</li><li>Made it run on port :443 so it looks like regular HTTPS traffic</li><li>Saved the infrastructure in Terraform IaC for one click deploy</li></ul></span> |
| [nat-instance-aws-terraform](https://github.com/ShobanChiddarth/nat-instance-aws-terraform) | <span><ul><li>Created an AWS architecture to replace AWS NAT Gateway with a self managed NAT instance</li><li>Saved [~$420/month for a ~$300/GB egress infrastructure](https://shobanchiddarth.hashnode.dev/i-recently-learnt-how-to-setup-a-nat-instance-instead-of-nat-gateway-in-aws#cost-calculation)</li><li>Saved the architecture as a Terraform repo for re-usability</li></ul></span> |
| [Containerized openssh-server](https://github.com/ShobanChiddarth/openssh-server) | <span><ul><li>Created a Docker container to host an OpenSSH server instance for LAN file transfer</li><li>Enhanced privacy in file transfer by requiring SSH authentication (SSH is encrypted by default)</li><li>Reduced cyber attacks by making SSH server instance delete after transfer is over so attack surface is reduced as SSH service is not permanently up in host</li></ul></span> |
| [randomised_mac_linux](https://github.com/ShobanChiddarth/randomised_mac_linux) | <span><ul><li>Created a script to spoof the MAC address of real network interfaces in a Linux desktop</li><li>Integrated the script with systemd to run on boot</li><li>Increased privacy of Linux desktop by reducing network-level spying and tracking</li></ul></span> |

## Open Source Contributions


### [SigmaHQ/sigma](https://github.com/sigmaHQ/sigma)

| PR | Opened on | Status | Description |
| --- | --- | --- | --- |
| [6618](https://github.com/SigmaHQ/sigma/pull/6118) | Jul 8, 2026 | Pending Merge (1 human maintainer approved, 1 more required for merge) | Contributed a Sigma rule to detect if "Block Public Access" settings of AWS S3 buckets were weakened (buckets made public) |

### [logpy/logpy](https://github.com/logpy/logpy)

| PR | Opened on | Status | Description |
| --- | --- | --- | --- |
| [85](https://github.com/logpy/logpy/pull/85) | Oct 23, 2025 | Merged | Fixed python collections module import statements as per new version 3.10+ |

### [jazzband/prettytable](https://github.com/jazzband/prettytable/pull/186)

| PR | Status | Opened on | Description |
| --- | --- | --- | --- |
| [186](https://github.com/jazzband/prettytable/pull/186) |  Jun 1, 2022 | Merged | Added `None` annotation to `__init__` functions |


### [numpy/numpy](https://github.com/numpy/numpy)

| PR | Status | Opened on | Description |
| --- | --- | --- | --- |
| [21692](https://github.com/numpy/numpy/pull/21692) | Jun 8, 2022 | Merged | Minor contribution: file renaming |
| [20949](https://github.com/numpy/numpy/pull/20949) | Jan 31, 2022 | Merged | Minor contribution: file renaming |

## Certifications

[![aws-certified-cloud-practitioner](https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?style=for-the-badge)](https://www.credly.com/badges/56f915f2-6b5d-4e3b-9188-04e10dea34d0/public_url)
[![google-cybersecurity-professional-certificate](https://img.shields.io/badge/Google_Cybersecurity-Professional_Certificate-4285F4?style=for-the-badge&logoColor=white)](https://www.credly.com/badges/495d0396-80c4-4aa2-ab3a-0431e5d340c6/public_url)

