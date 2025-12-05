| [Home](../README.md) |
 | -------------------------------------------- |

# Contents

The **Outbreak Response - UNC1549 Critical Infrastructure Espionage Attack** solution pack contains the following resources.

## Outbreak Alerts Record Set

| Name | Description |
|:-------------------------|:------------------|
| UNC1549 Critical Infrastructure Espionage Attack | A suspected Iran-linked espionage group tracked as UNC1549 is actively targeting aerospace, defense, and telecommunications organizations across Europe and other regions. The threat actor employs a combination of highly tailored spear-phishing, credential theft from third-party services, and the abuse of virtual desktop infrastructure such as Citrix, VMware, and Azure VDI to gain initial access and move laterally within target networks. |

## Threat Hunt Rules Record set

| Name | Rule Type |
|:-------------------------|:------------------|
| Detects CRASHPAD, a browser credential dumping utility used by UNC1549. | Yara |
| Detects DCSYNCER.SLICK, a modified Mimikatz-based utility used by UNC1549 | Yara |
| CVE-2020-0688 Exploitation via Eventlog | Sigma |
| CVE-2020-0688 Exchange Exploitation via Web Log | Sigma |
| ProxyLogon MSExchange OabVirtualDirectory | Sigma |


 <table><th>NOTE</th><td>These SIGMA and Yara rules are sourced from public community repositories are not independently verified or validated by Fortinet. While community-contributed rules can be valuable for timely threat detection, they may vary in quality, accuracy, and relevance. Fortinet is not responsible for any inaccuracies, errors, or omissions in these rules, nor for any damage or loss that may result from their application. We encourage users to conduct their own validation and adapt these rules as necessary to meet specific security needs and contexts</td></table> 

# Next Steps
| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
| ----------------------------------------- | ------------------------------------------- | --------------------- |
