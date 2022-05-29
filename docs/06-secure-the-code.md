---
sidebar_label: 'Secure The Code'
slug: /secure-the-code
---

# Secure The Code

 
![](images/06-secure-the-code.png)

This is about your code and external code – namely open source.

Use code scanning tools to ensure submitted code is high quality, safe and reliable – and conforms to best practice.  i.e. doing automated code reviews – that previously peers would have done.

Static code analysis tools helps identify areas in which areas of the code under analysis is suspect and may be compromised

Secure your secrets and put in the source code.   Once application source code is loaded into source control, it can spread widely and potentially be read by many.  Secrets – like API keys, security tokens, certificates and passwords are extremely sensitive as they open doors – so they must not be embedded into source code or they will leak.  Put such secrets in a safe storage service and then get the application to retrieve them at run time.

Software Composition Analysis tools should be employed to analyse the dependency graph and keep an inventory of third-party components being used to build applications. More on this later when we discusss the [Software Supply Chain](./10-software-supply-chain.md).

For private development store source code in well-secured code repositories. Fully understand your branch management so you know what code is in dev / test / production.  And have processes for hotfixes.

