---
sidebar_label: 'Secure By Design'
slug: /secure-by-design
---

# Secure By Design

![](images/05-secure-by-design.png)

Security Starts with the Design before any code is written.

The design will transform user requirements into an architecture containing the platform components and software modules to be developed, and will define how they interact.

Threat modelling is done by people with a mindset that will think like an attacker rather than a defender.   They will use a threat modelling metholodogy to tease out flaws in the design – which can then be addressed early,  when they are relatively easy and cost-effective to resolve.   

Zero Trust is response to the way networks have changed.  We use to have an internal network and an external network with a firewall between to keep the bad guys out.  Today your trusted people are working on untrusted networks – and 'assume beach', most likely there will be untrusted people on your trusted networks.  Today you have to protect resources not network segments. 

Core principal is everything is a threat - don’t trust anything or anyone at anytime until identity has been fully verified and you have a high level of assurance it is what it claims to be.  

- Verify explicitly - Always authenticate and authorize based on all available data points, including user identity, location, device health, service or workload, data classification, and anomalies
- Use least privileged access - Limit user access with just-in-time and just-enough-access (JIT/JEA), risk-based adaptive polices, and data protection to help secure both data and productivity.
- Assume breach - Minimize blast radius and segment access. Verify end-to-end encryption and use analytics to get visibility, drive threat detection, and improve defenses.

Identity is key and become a popular attack vector.  Do not revent your own identity - instead use industry standards and products/services from specialised organisations that have invested substantially in this and have offerings that are battle proven. 

Data Classification is knowing your data – is it Highly Confidential, Confidential, Public, Business, Non-Business.  Protect personal identifiable information (PII) becuase the Data Protection laws and regulations around that can impose heavy fines for any breach.

Confidential data should always be protected using encryption when sending over the wire or when stored at rest.

 
