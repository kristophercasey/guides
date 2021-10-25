# Common Terminology

### AAA
Authentication, Authorization, and Accounting
- **Authentication** - Authentication provides a method of identifying a user, typically by having the user enter a valid username and password before access to the network is granted. Authentication is based on each user having a unique set of login credentials for gaining network access.
- Methods of authentication as it relates to a person's identity:
  - Something you know
  - Something you are
  - Something you have
  - Something you do
  - Somewhere you are  
- **Authorization** - Following authentication, a user must gain authorization for doing certain tasks. After logging in to a system, for instance, the user may try to issue commands. The authorization process determines whether the user has the authority to issue such commands. Authorization is the process of enforcing policies—determining what types or qualities of activities, resources, or services a user is permitted. Usually authorization occurs within the context of authentication. After you have authenticated a user, they may be authorized for different types of access or activity.
- **Accounting** - The final piece in the AAA framework is accounting, which monitors the resources a user consumes during network access. This can include the amount of system time or the amount of data sent and received during a session. 
> Reference(s): https://www.arubanetworks.com/techdocs/ClearPass/6.7/Aruba_DeployGd_HTML/Content/802.1X%20Authentication/About_AAA.htm

### AirGap
An airgap isolates a computer from the network as it has no physical or wireless connections. The only way to extract data is by removable media.
> Reference(s): Neil, Ian. CompTIA Security+: SY0-601 Certification Guide

An interface between two systems at which (a) they are not connected physically and (b) any logical connection is not automated (i.e., data is transferred through the interface only manually, under human control).
> Reference(s): https://csrc.nist.gov/glossary/term/air_gap  

### Playbook
A playbook is a list of required steps and actions needed to successfully respond to any incident or threat. Playbooks provide a step-by-step approach to orchestration, helping security teams to establish standardized incident response processes and ensuring the steps are followed in compliance with regulatory frameworks. 

### Runbook
Runbooks can automate and carry out the early-stage processes of evaluating and examining security incidents until a human analyst is needed to intervene. They can automate the threat management operations from detection and triage to investigation and containment. For example, in a spearphishing runbook, indicators are extracted from the phishing email, checked through different threat services, and subsequently, blocked if they are found malicious.  
> Reference(s): https://cyware.com/educational-guides/security-orchestration-automation-and-response/what-is-the-difference-between-a-security-playbook-and-a-runbook-ddc4/

### SIEM
A Security Information and Event Management (SIEM) is an application that provides the ability to gather security data from information system components and present that data as actionable information via a single interface.
> Reference(s): https://csrc.nist.gov/glossary/term/security_information_and_event_management_tool  

### CIA Triad Concept
The three pillars of information security - Confidentiality, Integrity and Availability (CIA). 
- **Confidentiality** – preserving authorized restrictions on information access and disclosure, including means for protecting personal privacy and proprietary information  
- **Integrity** — guarding against improper information modification or destruction and ensuring information non-repudiation and authenticity  
- **Availability** – ensuring timely and reliable access to and use of information  
> Reference(s): https://www.nccoe.nist.gov/publication/1800-25/VolA/index.html  






