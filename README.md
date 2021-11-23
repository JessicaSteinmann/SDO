# Security Development Ontology - SDO
Page last updated: 11/23/2021. 
V.1.0.0

Adding and revising definition of classes in protege.

This repository houses the security development ontology (SDO).
Available Ontohub!
Availability through Kbox on 12/15/2021.

The Secure Development Ontology (SDO) purpose is to assist with the elicitation of security requirements and design decisions. 
The ontology defines 183 core entities and 32 object properties. 
The SDO is implemented in Web Ontology Language 2 through the Protégé 5.5.0 tool. 

Current Classes:
1)	Actor: This class identifies users that interact with the system and classifies them as malicious or non- malicious users. This class contains 2 subclasses: Malicious Actor and Non-Malicious Actor. Malicious Actor contains individuals such as Attacker, Disgruntled Employee, and Botnets. Non-Malicious Actor contains individuals such as Business analysts, Penetration Tester, Developer, Risk Analysts, Quality Assurance Analysts, etc. 
2)	Attack: This class identifies attacks that can occur to a system. This class contains 16 subclasses such as Brute Force, Cross Site Scripting (XSS), Man in the Middle, Account Lockout, etc.
3)	Mitigation: This class identifies mitigations to attacks and vulnerabilities in systems. This class contains 10 sub-classes such as Client-Side Certificates, Delays, Encryption, Hashing, Logging, Monitoring, etc.
4)	Security: This class identifies the CIA triad. This class contains 3 sub-classes: Confidentiality, Integrity, Availability. It allows the categorization of attack, mitigation, and vulnerability by CIA triad principles. 
5)	Vulnerability: This class identifies vulnerabilities that can exist in a system. This class contains 14 sub-classes such as Broken Access Control, Insecure Deserializations, Leaked Credentials, Security Misconfigurations, Insufficient Logging, Insufficient Monitoring, etc.   
6)	Development Life Cycle Stage: This class identifies the life cycle stage for the consideration of the security concept. This class contains 5 sub-classes: Requirement, Design, Implementation, Testing, Maintenance. 
