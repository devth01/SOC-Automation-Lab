# SOC Automation Lab

## Objective

This lab project was developed to simulate and detect cyber attacks in a controlled environment, with a focus on identifying the use of Mimikatz.exe—a tool commonly used to extract plaintext credentials from Windows memory and perform code injection. The core objective was to generate test telemetry that reflects real-world attack behavior and analyze the resulting logs through a SIEM platform. This hands-on setup provided valuable experience in network defense, threat detection, and understanding how different attack techniques can be identified and mitigated using modern security tools.

### Skills Learned

- Gained a strong understanding of how SIEM systems operate, including core concepts and real-world application.
- Improved ability to analyze network logs and identify meaningful security events.
- Developed the skills to explain attack signatures and deepened knowledge of common security vulnerabilities.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Experienced real-time alerting scenarios, which enhanced problem-solving skills in cybersecurity.

### Tools Used

- **SIEM & Log Management**  
  - Wazuh (manager and agent)  
  - Filebeat (log shipper)  
  - Sysmon (Windows system monitoring and event logging)

- **Threat Detection & Response**  
  - TheHive (case management platform)  
  - Shuffle SOAR (automated alert handling and workflow orchestration)

- **Monitoring & Visualization**  
  - Wazuh Dashboard (real-time alert monitoring)

- **Operating Systems & Environments**  
  - Ubuntu (Wazuh server and Shuffle host)  
  - Windows 10 VM (endpoint with Sysmon for attack simulation)

- **Infrastructure & Network Security**  
  - VirtualBox (for local virtualized test environments)  
  - Custom firewall rules (for cloud VM segmentation and security testing)

### Network Architecture Diagram

