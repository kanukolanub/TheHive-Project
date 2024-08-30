# TheHive-Project

## Overview

This repository contains a project on how to use TheHive, a Security Incident Response Platform, to report investigation findings.

## SCENARIO
You have captured network traffic on your network after suspicion of data exfiltration being done on the network. This traffic corresponds to FTP connections that were established. Your task is to analyse the traffic and create a case on TheHive to facilitate the progress of an investigation. 

## PROJECT
Analyse the FTP traffic and create a case on TheHive to facilitate the progress of an investigation. 
* Key Topics: FTP Traffic, Data Exfiltration
* Tools: TheHive, FTP PCAP file.

Once an analyst has logged in to the dashboard, they will be greeted with the screen below. At the top, various menu options are listed that allow the user to create new cases and see their tasks and alerts. A list of active cases will be populated on the centre console when analysts create them.

![image](https://github.com/user-attachments/assets/ba6bf67a-dc96-4504-af79-07da46cab68a)

On clicking the New Case tab, a pop-up window opens, providing the analyst with fields to input their case details and tasks. The following options must be indicated on the case to set different categories and filter options:

* Severity: This showcases the level of impact the incident being investigated has on the environment from low to critical levels.
* TLP: The Traffic Light Protocol is a set of designations to ensure that sensitive information is shared with the appropriate audience. The range of colours represents a scale between full disclosure of information (White) and No disclosure/ Restricted (Red).
* PAP: The Permissible Actions Protocol is used to indicate what an analyst can do with the information, whether an attacker can detect the current analysis state or defensive actions in place.
  
![image](https://github.com/user-attachments/assets/2bc227e1-40ab-4bf4-bce4-e9005b47a528)

![image](https://github.com/user-attachments/assets/ef0fec21-be92-453c-ab98-ef6b921e6989)

In the visual below, we add the corresponding tactic and technique associated with the case. The TTPs are imported from MITRE ATT&CK. This provides additional information that can be helpful to map out the threat. As this is an exfiltration investigation, that is the specific tactic chosen and followed by the specific T1048.003 technique for Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol.

clcik on TTPs tab, and click +Add TTP
![image](https://github.com/user-attachments/assets/4572740a-6c86-4aeb-b2ed-f18a13e647f1)

Tasks Tab
![image](https://github.com/user-attachments/assets/08dd5bc1-0fd4-4ce4-b5b2-512e6f2182d1)

