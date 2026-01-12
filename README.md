

## 4.1 Cybersecurity Devices and Technologies
### 4.1.1 Security Appliances
- 6 Categories 
- 1. Routers
- 2. Firewalls
- 3. IPS - Intrusion Prevention System
- 4. VPN - Virtual Private Network
- 5. Antivirus / Antimalware
- 6. Other Security Appliances - web/email security, other tools


<br>
<br>
## Firewalls
- Control which communications are allowed in/out.
- Installed in one computer or can be a standalone network device.

### Types of Firewalls
- 1. Network layer - source/destination ip
- 2. Transport layer - source/destiation port, connection states
- 3. Application layer - application, program or service
- 4. Context aware - user, device, role, application type and threat profile
- 5. Proxy Server - web content requests (urls, domain names and media types)
- 6. Reverse Proxy - hide or offload and distribute access to web servers.
- 7. Network Address Translation (NAT) firewall - hides the private addresses of network hosts.
- 8. Host-based firewall - ports/system srvice calls on a single computer OS

<br>
<br>
###  Port Scanning 
- each app running in a device is assigned a port number
- port is used on both ends of the transmission so that right data is passed to the correct app
- Port scanning is a process of probing a computer
- Example Applications:
  - nmap online port scanner
  - zenmap

<br>
### Intrusion Detection and Prevention Systems
- IDS and IPS
- Deployed on a network to detect and prevent malicious activities
- IDS - can be dedicated network device, tools in a server, frewall, host OS.
- Scan data against a database of rules or attack signatures, looking for malicous traffic.
- Job is to alert, detect, log and report. It will not take action to prevent attackes from happening.

- IPS - block or deny traffic based on a rules or signature match.

<br>
<br>
### Real-Time Detection
- Requires actively scanning for attacks using firewal and IDS/IPS network devices. 


### Protecting Against Malware
- One way is to use an enterprise-level advanced malware detection solution

### Security Best Practices
- Some guides are found in National Institute of Standards and Technology (NIST) Computer Security Resource Center.

- 1. Perform risk assessment
- 2. Create a security policy
- 3. Physical security measures
- 4. Human resources security measures
- 5. Perform and test backups
- 6. Maintain security patches and updates
- 7. Employ access controls
- 8. Regularly test incident response
- 9. Implement a network monitoring, analytics and management tool
- 10. Implement network security devices
- 11. Implement a comprehensive endpoint security solutions
- 12. Educate users
- 13. Encrypt data

<br>
<br>
<hr>

## Behavior Approach to Cybersecurity
<br>
### Behavior-based Security
- Form of threat detection that involves capturing and analyzing the flow of communication. Any changes in normal pattern can be regarding as **anomalies**

- Honeypots - behavior based detection tool, lures attacker in by applearing to their predicted pattern. Capture and analyze their behavior so that they can build a better defense.

<br>
### NetFlow
- gather information flowing through a network
- who, what devices, when and how users accesss the network

<br>
### Penetration Testing
- assessing a computer system, network or organization for security vulnerabilities. 
- seeks to breach systems, people, porcesses and code to uncover vulnerabilities which could be exploited.

- 5 Step pen test process
- 1. Planning - gathers information
- 2. Scanning - active reconnaissance 
- 3. Gaining Access - 
   - launching an exloit with a payload onto the system
   - breaching the physical barriers to assets
   - social engineering
   - exploiting website vulnerabilities
   - exploting software/hardware vulnerabilities or misconfigurations. 
   - breaching access controls security
   - cracking weak encrypted Wi-Fi

- 4. Maintining Access - examples are, Trojan horses, rootkits, and other covert channels.
- 5. Analysis and reporting - provide feedback that recommens updates to products, policies and training to improve an organization's security.

<br>
<br>
### Impact Reduction
- No set of security practices is foolproof.
- Actions to do when breached is identified:
- 1. Communicate the issue
- 2. Be sincere and accountable
- 3. Provide the details
- 4. Find the cause
- 5. Apply lessons learned
- 6. Check, and check again
- 7. Educate!

<br>
<br>
### Risk Management
- Continuously identifying and assessing risk in an effor to reduce the impact of threas and vulnerabilities. 
- You cannot eliminate risk completely. But you can reduce the impact.
- 1. Frame the risk - identify threats that increase risk. May include:
  - process
  - products
  - attackes
  - potentical failure or disruption of services
  - negative perception of an organization's reputation 
  - potential legal liability  or loss of IP

- 2. Assess the Risk - quantitative and qualitative analysis
- 3. Respond to the Risk - action plan  to reduce overall org risk exposure
    - eliminated 
    - mitigated
    - transferred
    - accepted
- 4. Monitor the Risk - elimnation, mitigation or transfer actions. Closely monitor any threas that have been accepted. 

<br>
<br>
<hr>
## Cisco's Approach to Cybersecurity
### Security Playbook
### Tools for Incident Detection and Prevention
- SIEM - Security Information and Event Management 
- DLP - Data Loss Prevention System
- ISE - Identity Services Engine

<br>
<br>
<hr>
## Ethical Dilema
- https://www.netacad.com/content/i2cs/7.1/courses/content/m5/en-US/assets/module5.pdf

<br>
<br>
<hr>


# Understanding the Basic Components of a Computer
<br>
## CPU
- Central Processing Unit
- Brain of Computer
- Key Parts
  - ALU - Aritchmetic Logic Unit - performs arithmetic (add,sub) and logical operations (AND,OR, NOT)
  - Control Unit - coordinates most of the operations, managing data flow
  - Registers - hold data


- Key Metric
  - Cores - number of independent processing units
  - Threads - number of instructions streams a CPU can handle simultaneously
  - Clock Speed (GHz) - number of cycles the CPU can perform per second.
  - Cache Memory (L1, L2, L3) - store frequently accessed data.

<br>

## RAM
- stores data and program instructions that the CPU needs to access quickly.
- Key Metrics
  - Capacity (GB)
  - Speed - MHz or MT/s MegaTransfers per second.

<br>
## Motherboard
- main Printed Circuit Board (PCB)
- serves as the central communication backbone for all the hardware components.
- connects everything together
- Think of it as a nervous system

- Key Components
1. CPU Sockets 
2. RAM Slots (DIMM slots) - Dual Inline Memory Module
