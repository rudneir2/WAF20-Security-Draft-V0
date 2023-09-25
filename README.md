# WAF20 Security Draft V0

## Introduction to IT common environment and Microsoft Security services considered in WAF Security recommendations

Microsoft Well-Architected Framework helps you understand how to apply the best practices in using Microsoft Security services in your IT environment based on Recommendations in different segments such as Security patterns, Application Secrets, Encryption, “Identity and Access”, Networking, Segmentation and “Test and validation”.
There are also other approaches that cover Microsoft security and its best practices, so it is important to understand what the main objective of WAF is.
Below is a diagram that depicts what Microsoft security services are considered in WAF and different approaches, including the threats and the different methodologies that may be used to map threats.

![image](https://github.com/rudneir2/WAF20-Security-Draft-V0/assets/97529152/0727b2ed-d1aa-4b88-8f7b-23780edc9cc3)

## A common IT environment example

Before diving into different WAF segments and their recommendations based on Microsoft security services, it is important to understand how to apply those recommendations in a real IT environment. To make that understanding easier, below there is a very common IT environment that may be found in many companies from different industries.

![image](https://github.com/rudneir2/WAF20-Security-Draft-V0/assets/97529152/a5b30eb3-b925-4e2c-b322-c7f54e9a0e4e)

The IT environment above describes a hybrid IT environment with a layer of Azure public cloud, an on-premises, and Office 365 public services. Each box describes some of the common services.
Now, let’s include the layer of threats so we may understand the different threat actors that may be involved in an attack and the different tactics, techniques, and tools to compromise the IT environment.

## An example of a Threat Map

Most common Threats diagram includes some examples of tactics and techniques based on the Mitre Attack matrix and some examples of tools that are used by attackers.
It also includes some of the threat actors that may start an attack, such as remote admins, remote employees, your company’s clients, external developers that are not in the on-premises network perimeter, and any anonymous attacker that may initiate an attack against your environment.

![image](https://github.com/rudneir2/WAF20-Security-Draft-V0/assets/97529152/3b7f1358-2dd7-4607-8a95-68ca1f5e93c5)

## Adding Azure Security services to the diagram

Before we dive into details for each WAF recommendation, let’s understand how different security services may be grouped so you have a better understanding of how to apply them according to WAF recommendations in different segments.
Below let’s include some of the most important Azure Security services, usually considered in the pre-breach phase, to protect and prevent some types of attacks. The diagram below is just a simple example, that will be detailed in each WAF recommendation segment.

![image](https://github.com/rudneir2/WAF20-Security-Draft-V0/assets/97529152/e559b323-736e-458c-8836-5c971874c550)

## Azure Monitoring Services

This next diagram adds a layer with Azure monitoring, SIEM (Microsoft Sentinel), SOAR (Incident response automation), CSPM (Microsoft Defender for Cloud) capabilities that work totally integrated with Azure resources and Azure Security services.

![image](https://github.com/rudneir2/WAF20-Security-Draft-V0/assets/97529152/7e825fdb-4f12-446d-8869-7775341cf5b5)

## Microsoft 365 Defender and Purview Compliance integrated with Azure Security 
### * that is a PLUS that might be added to WAF Security recommendations, part of the Segments sections

Lastly, this next diagram adds the Microsoft 365 Defender solutions and Purview Compliance solutions that may be used in the pre-breach and post-breach phases, protecting the entire IT environment, including on-premises, Azure environment, and Office 365resources, still fully integrated with Azure security services.



In the next sections, we will detail the services involved in each WAF segment, and how it works to protect, prevent, and identify threats based on a real common IT environment.

