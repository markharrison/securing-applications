---
sidebar_label: 'Secure The Environment'
slug: /secure-the-environment
---

# Secure The Environment

![](images/07-secure-the-environment.png)

When using cloud there is shared responsibilities for securing the environment .  The cloud vendor will handle the physical security but the users must secure their own environments and resources.
Analogy is a castle - doesn’t matter how high the walls are / how many crocodiles are in the moat is around our castle – if you leave the drawbridge down  … then an intruder can easily walk in and party in your castle. 

Access controls are used to impose rules on who can access what and what level of access they have.  Dev environments maybe more relaxed but access to production environments should be strictly controlled and limited.   Access controls need to combine with a strong identity foundation and use features such as conditional access, multi-factor authentication,  just-in-time and just-enough-access (JIT/JEA).

Policy services are used to centrally set guardrails throughout your resources to help ensure cloud compliance, avoid misconfigurations, and practice consistent resource governance.   
 
'Infrastructure as Code’ is the practice of keeping infrastructure topology specified in scripts/templates and are stored in version control - in a similar fashion to the way developers manage code / deploy solutions. It then enables consistency, quality, repeatability and accountability of the configuration. 

Network security controls / devices may be implemented to mitigate against various known attack vectors. Application security often involves discussion around networking such as firewalls / gateways / load balancers – and ensuring the infrastructure is locked down from certain types of network attacks.

Ensure patching to ensure all known vulnerabilities in virtual machines / operating system instances are resolved. If using PaaS – then not an issue, and its handled automatically / transparently by the underlying system. But its still a relevant topic in some cloud-native services – such as if using Kubernetes. 

 