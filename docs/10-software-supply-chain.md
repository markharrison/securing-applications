---
sidebar_label: 'Software Supply Chain'
slug: /software-supply-chain
---

# Software Supply Chain
 
![](images/10-software-supply-chain.png)

Open source is software made available with source code that anyone can inspect, modify, and enhance. It is provided with a license that dictates how the software can be used – for example, it might impose commercial restrictions or mandate that any modifications must also be shared back with the community.

It is important that organizations understand and mitigate against the risks of open source. When an open source library is imported/used, then all the dependencies that library uses is also included – and there could be many levels of dependencies resulting in the use of considerable amounts of software from unknown sources.

Infecting popular open source libraries with malware / vulnerabilities is on the rise - this is known as a software supply chain attack.  It can wreak maximum havoc as the malware will be further distributed to all users of the software that includes the library code.

Software Composition Analysis tools should be employed to analyse the dependency graph and keep an inventory of third-party components being used to build applications – these can then provide ongoing monitoring to:

- Report on known security vulnerabilities and software bugs.
- Alert when updated versions are available.
- Accurately track the open source licensing conditions to fulfil all the legal requirements helping to avoid any unfortunate surprises … such as jeopardizing exclusive ownership over proprietary code.

Such tools can help software vendors document their Software Bill of Materials (SBOM) which lists any components, libraries and tools used.   There has been discussion that future legislation may force software companies to make SBOM declarations public.

