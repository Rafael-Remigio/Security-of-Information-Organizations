# Vulnerabilities


When developing a System bugs and (design) flaws are introduced into systems, sometimes reaching exposed interfaces, and becoming a vulnerability to the correct execution of the system.

## **Vulnerability** 

Is a mistake in the software that can be directly used by an attacker to gain access to a system or network. A mistake is a vulnerability if it allows an attacker to violate a Security Policy in a System

A software coding error that is used by hackers to enter an information system and perform unauthorized activities while posing as an authorized user

## **Exposure**

Exposure is a necessary, but not sufficient, determinant of risk. It is possible to be exposed but not vulnerable (for example by living in a floodplain but having sufficient means to modify building structure and behaviour to mitigate potential loss). However, to be vulnerable to an extreme event, it is necessary to also be exposed.

A configuration issue or a mistake that does not directly allow comprimise (nonetheless an exposure can still be an important component of an attack)

#
## Security Measures

* Discouragement
    * Punishment
    * Security barriers
* Detection
* Deception
* Prevention
* Recovery

**Discouragement, Detectio and Deception** tackle mainly known Issues
* Reconnaissance attemps
* Generic attacks
* Specific attacks

**Prevention** tackle well-known and unknown **Vulnerabilities**
* Generic Vulnerabilities
* Specific Vulnerabilities

**Revovery**
* Backups
* Redundancy
* Forensic Recovery

### Enforcment of measures requires specific knowledge

* Known vulnerabilities
* Activity patterns used in attacks
* Abnormal activity patterns

**Computer network Threats** are unlike any other threats beacause:
* They can be lauched at any time and anywhere
* Can be easily coordinated (DDOS for example)
* Cheap to deploy
* They can be automated
* Fast

For this reason we require a permanent 24x7 capacity to react

#

## CVE -> Common Vulnerabilities and Exposures 

Dictionary of Publicly known information security Vulnerabilities and Exposures

### Benefits of CVE
* Facilitates Understanding and discovering Vulnerabilities
* Will lead to improvment in security tools
* Will spark further innovation

### Vulnerabily detection
Specific tools can detect Vulnerabilities and replicated known attacks, these are vital to assert the robustness of production systems and applications. Can be applied to Source Code, Running application, remote clients.

## CWE -> Common Weakness Enumeration

Common Language of discourse for discussing, finding and dealing with the causes of software security vulnerabilities. 
Found in code, design and architecture, and each CWE represents a type of vulnerability

Held in hierarchical Structure


## Vulnerability Tracking
* Helps focusing the discussion around the same issue
* Helps defenders to easily test their systems, enhacing their security
* Helps attackers to easily know what vulnerabilities can be used


Vulnerabilities are also weapons and a business
* They can constitute an arsenal against future attacker
* Exploits are Weapons
* Can be Sold, either to other attackers or to the vulnerable company (google for example pays for bug finding, but can also be sold to Organized Crime)

## **Zero Day / Zero Hour Attack/Threat** 
Refers to attacks using vulnerabilities unknown before. No security fix is yet available

How to survive Zero Day attacks?
* Diversity in software
* **(CERT)** Computer Emergency Readiness Team
* **(CSIRT)** Computer Security Insidence Response Team

#

## Vulnerability Types
* Injection
* Broken authentication
* Sensitive data exposure
* XML external entities
* Broken Access Control
* Security Misconfigurations
* Cross-Site-Scripting (XSS)
* Insecure Deserialization
* Using Components with known vulnerabilities
* Insufficient Logging and monitoring

#