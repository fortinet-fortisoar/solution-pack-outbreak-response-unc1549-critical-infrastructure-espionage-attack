# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

A suspected Iran-linked espionage group tracked as UNC1549 is actively targeting aerospace, defense, and telecommunications organizations across Europe and other regions. The threat actor employs a combination of highly tailored spear-phishing, credential theft from third-party services, and the abuse of virtual desktop infrastructure such as Citrix, VMware, and Azure VDI to gain initial access and move laterally within target networks. 

 The **Outbreak Response - UNC1549 Critical Infrastructure Espionage Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.3.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/unc1549-espionage-attack) contains information about the outbreak alert **Outbreak Response - UNC1549 Critical Infrastructure Espionage Attack**. 

## Background: 

Since mid-2024, UNC1549 has been executing highly targeted espionage campaigns against organizations in the aerospace, aviation, and defense sectors. The group gains initial access through tailored spear-phishing aimed at credential theft and malware delivery, as well as by compromising trusted third-party access and supply-chain relationships to pivot into downstream environments.

The threat actor has previously leveraged CVE-2021-26855 and CVE-2020-0688 in past campaigns to gain initial access and facilitate follow-on exploitation.

UNC1549 employs multiple custom malware families and covert operational techniques to establish persistence and evade detection:
- MINIBIKE: Modular backdoor enabling credential theft, keylogging, screenshot capture, and deployment of additional payloads.
- TWOSTROKE: Remote access tool designed for persistence and full host control.
- DEEPROOT: Linux-focused variant providing similar capabilities across non-Windows platforms.
- LIGHTRAIL & GHOSTLINE: Covert C2 and tunneling tools that disguise malicious traffic within legitimate cloud services to support resilient communications and data exfiltration.

These operations are consistent with state-sponsored intelligence requirements, emphasizing the theft of sensitive technical data, monitoring of high-value communications, and maintaining long-term strategic footholds inside targeted environments. 

## Announced: 

Fortinet customers are protected through the FortiGuard Intrusion Prevention System (IPS) Security Service, which detects and blocks exploit attempts targeting known vulnerabilities associated with this activity. In addition, FortiGuard provides coverage against malware leveraged throughout the campaign. For the complete list of available protections, please refer to the Solution tab.

 

## Latest Developments: 

November 27, 2025: FortiGuard released a Threat Signal Report on UNC1549 Critical Infrastructure Espionage Attack.
https://www.fortiguard.com/threat-signal-report/6276/unc1549-critical-infrastructure-espionage-attack

November 17, 2025: Google Released Frontline Intelligence: Analysis of UNC1549 TTPs, Custom Tools, and Malware Targeting the Aerospace and Defense Ecosystem.
https://cloud.google.com/blog/topics/threat-intelligence/analysis-of-unc1549-ttps-targeting-aerospace-defense

February 27, 2024: Mandiant released a blog post about suspected Iran-nexus espionage activity targeting the aerospace, aviation and defense industries in Middle East countries, including Israel and the United Arab Emirates (UAE) and potentially Turkey, India, and Albania. 
https://cloud.google.com/blog/topics/threat-intelligence/suspected-iranian-unc1549-targets-israel-middle-east

March 12, 2021: FortiGuard Labs released an Outbreak Alert for Microsoft Exchange Server remote code execution (RCE) vulnerabilities. These same vulnerabilities have previously been exploited by UNC1549 to gain initial access into target networks, highlighting the ongoing risk posed by unpatched or misconfigured Exchange servers.
https://www.fortiguard.com/outbreak-alert/microsoft-exchange 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
