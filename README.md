![alt tag](https://user-images.githubusercontent.com/24201238/29351849-9c3087b4-82b8-11e7-8fed-350e3b8b4945.png)

# Panopticon Project

## Name - C-06
* Label - Advanced Persistent Threat (APT) 

## Aliases
Other names the threat actor is known by.
Use list
* [Alias](URL to source)
* [Alias](URL to source)

## Overview - end of header
A high-level summary of the threat actor.
Use list
* Description goes here
*

## Time context starts

## Campaign or Date Range - start of repeatable time contextual section 
Use either a campaign with a specific timeframe or a date range not associated with a specific campaign. About is a short description of the campaign and should be removed if using date range. Dates should be in the format of DD Month Year e.g. 01 January 2019.
* Campaign / Date Range
* About - [Targeting infrastructure in South East Asia](URL to source)
* Active from - XX Month 20XX
* Active to - XX Month 20XX

### Attributes
Listed after Campaign or Date Range as attributes can shift over time. Use one of the resource levels. Use one of the sophistication grades. Amateur is defined as using all prewritten tools and/or showing overall poor tradecraft. Expert is defined as using at least some self-written tools and/or showing overall good tradecraft. Advanced Expert is defined as consistently using self-written tools and showing consistently good tradecraft. Primary activity is a short description of what the groups mostly does.
* Resource level - [Individual / Group / Corporation / Government](URL to source)
* Sophistication - [Amateur / Expert / Advanced Expert](URL to source)
* Primary activities - Description goes here

### Attack Pattern
See the [Enterprise Matrix](https://attack.mitre.org/) for definitions of each of the below areas. Use in the order they occur and state no information for entries that don't yet have any information. Malware should have a short description and be detailed below.
Use list
* Initial Access 
  * [Attack Pattern](URL to source)
  * Description
* Execution
  * [Attack Pattern](URL to source)
  * Description
* Persistence
  * [Attack Pattern](URL to source)
  * Description
* Privilege Escalation 
  * [Attack Pattern](URL to source)
  * Description
* Defence Evasion 
  * [Attack Pattern](URL to source)
  * Description
* Credential Access
  * [Attack Pattern](URL to source)
  * Description
* Discovery
  * [Attack Pattern](URL to source)
  * Description
* Lateral Movement
  * [Attack Pattern](URL to source)
  * Description
* Collection
  * [Attack Pattern](URL to source)
  * Description
* Exfiltration 
  * [Attack Pattern](URL to source)
  * Description
* Command and Control 
  * [Attack Pattern](URL to source)
  * Description
* Malware - Description goes here

### Vulnerabilities
A mistake in software that can be directly used by an attacker to gain access to a system or network. Link to a writeup in the exploit repo where possible (example, CVEs) or to external sources. Format should be in the format of vulnerability is exploited by name of the thing exploiting it, usually malware or a hacking tool. State no information if no information is available.
Use list
* [Vulnerability](URL to outline of how vulnerability is exploited) is exploited by name of malware / name of tool
* [Vulnerability](URL to outline of how vulnerability is exploited) is exploited by name of malware / name of tool

### Identity
Individuals, organizations, or groups. These are represented as individual entries under the heading of Identity.

#### Individuals 
Specific members of threat actor. State no information for entries that don't yet have any information.
Use list
* [Name](URL to source)
* [Name](URL to source)

#### Affiliated organisations
Specific organisations the threat actor is connected to. State no information for entries that don't yet have any information.
Use list
* [Organisation](URL to source)
* [Organisation](URL to source)

#### Affiliated groups
Specific groups the threat actor is connected to. State no information for entries that don't yet have any information.
Use list
* [Group](URL to source)
* [Group](URL to source)

### Intrusion Set
A grouped set of adversarial behaviours and resources with common properties believed to be orchestrated by a single threat actor. These are represented as individual categories under the heading of Intrusion Set. If an existing category does not cover what you need to add, contact a project maintainer on panopticonproject at protonmail dot com to add a section to Charon.

#### Malware
Details of malware used. Multiple names should be listed on the same line and separated by a comma. Functionality should be short, preferably one word. Example: keylogger. Multiple functionalities should be listed on the same line and separated by a comma. Hash should have a -, the type of hashing function used, another -, and the hash itself. Example: Hash - MD5 - 002ae76872d80801692ff942308c64t6. Notes should be a short description of anything else important, like the family the malware belongs to or variants. State no information for entries that don't yet have any information.
* Names - [Name of malware](URL to source)
  * Functionality - add functionality
  * Hash - [Function] - [Actual hash](URL to source)
  * Notes - Description goes here

#### Website 
A website used by the attacker. URLs should be in the format of hxxp so people don't accidentablly navigate to the URL by clicking on it. IP addresses shouldhave square brackets [] arond the last separator so people don't accidentally navigate to the address. Dates should be in the format of DD Month Year e.g. 01 January 2019. State no information for entries that don't yet have any information.
* Name - Name of website
  * About - Description goes here
  * URL - [hxxp://address[.]com](URL to source)
  * IP - [000.000.000[.]000](URL to source)
  * Valid from - [XX Month 20XX](URL to source)
  * Valid to - [XX Month 20XX](URL to source)

#### Command and Control Server
A server used by the attackers to send commands to malware and to receive commands and exfiltrated information from the malware.
* About - used by Even More Muffins malware to receive commands from and exfiltrate data to. IP addresses should have square brackets [] around the last separator so people don't accidentally navigate to the address. Dates should be in the format of DD Month Year e.g. 01 January 2019.
* IP - [000.000.000[.]000](URL to source)
  * Valid from - [XX Month 20XX](URL to source)
  * Valid to - [XX Month 20XX](URL to source)
  * [SSH host key] (URL to source)
    * RSA - fingerprint
    * ECDSA - fingerprint
    * ED25519 - fingerprint
  * [SSL Certificate](URL to source)
    * Issuer - Name
    * Public key type - RSA etc
    * Public key bits - Bit length
    * Signature algorithm - name of algorithm
    * Not valid before - XX Month 20XX
    * Not valid after - XX Month 20XX
    * MD5 - MD5 hash
    * SHA-1 - SHA-1 hash
  * Notes - notes go here.

#### Documents
A document used by the attackers, usually as part of phishing. About should be a short description of how the document was used. Hash should have a -, the type of hashing function used, another -, and the hash itself. Example: Hash - MD5 - 002ae76872d80801692ff942308c64t6.
* Filename - [Name](URL to source)
  * About - Description goes here
  * Hash - Function - Actual hash
  * Notes - Notes go here

#### Tools
A tool used by the attacker. Multiple names should be listed on the same line and separated by a comma. functionalities should be short, preferably one word. Example: keylogger. Multiple functionalites should be listed on the same line and separated by a comma. URL should be the online address, if any, the tool can be publicly sourced from.
* Names - [Name of tool](URL to source)
  * Functionality - Functionality, functionality 
  * URL - http://address.com

## Time context ends

### Detection - end of repeatable time contextual section 
An action taken to detect an Attack Pattern entry. These should address the Attack Patterns listed above. State no information if no information is available.
Use list
* [Attack Pattern or Vulnerability entry goes here](URL to source)
  * Description

### Course of Action 
An action taken to either prevent an attack or respond to an attack. These should address the Attack Patterns and Vulnerabilities listed above. If the course of action is connected to something in this report, such as a CVE for example, that should be referenced. Example: Apply patch 5678 to ICS systems to patch CVE-2019-0254. State no information if no information is available.
Use list
* [Attack Pattern or Vulnerability entry goes here](URL to source)
  * Description

### YARA rules
Rules for detecting indicators of compromise. State no information where the rule would be pasted if no information is available.
Use list
* Rule - Paste on next line

* URL - http://address.com
  
### Reports 
Collections of threat intelligence focused on one or more topics, such as a description of a threat actor, malware, or attack technique, including contextual details. The description should be a short outline of the report.
Use list
* [Name of report](URL to pdf/blog post etc) - Description goes here
* [Name of report](URL to pdf/blog post etc) - Description goes here

## Copy and paste everything from Campaign or Date Range through to Reports for a new campaign or date range

## Raw Intelligence - start of footer
Any further notes to be added to the framework would be added here.

## Links - end of footer
https://blog.360totalsecurity.com/en/analysis-cve-2018-8174-vbscript-0day-apt-actor-related-office-targeted-attack/?utm_source=hs_email&utm_medium=email&utm_content=63229703&_hsenc=p2ANqtz--vrom6eZW3D9TkeA-sn7uL1sCRv4X1ZNQcjXyyuIy49lSaTzHHXLuRrb5MrfEU-vAr6gZ2Qtf6kGZ852ACy4TwGjM5wg&_hsmi=63229703
