# Risk Assessment

My collection of files from my studies.

This will determine the risk to Mass Driver Research, Inc.

This will cover the 4 main risk assessment parameters of FAIR and the OWASP top ten definitions.

Table of Contents
=================

   * [Risk Assessment](#risk-assessment)
      * [4 Main Risk Assessment Parameters of FAIR](#4-main-risk-assessment-parameters-of-fair)
         * [Other FAIR Definitions](#other-fair-definitions)
      * [Definitions of the OWASP Top 10](#definitions-of-the-owasp-top-10)

## 4 Main Risk Assessment Parameters of FAIR

Definitions: 

* Threat capability

Threat capability is the estimated capability of the threat agent or agents.

* Contact frequency

Frequency of encountering the risk

* Probability

Likelihood of the threat causing damage

* Resistance Strength

### Other FAIR Definitions

* Threat Agent Model

People, things, *or* groups of either.

Not all threats imply malicious intent, either.

## Definitions of the OWASP Top 10

OWASP tracked the breaches and incidents of major governments and organizations. 

The compiled the top ten of the common reasons for breaches. 

They're the most statistically likely vulnerabilities to affect an infrastructure, application, or human-mediated processes.

There's a broad consensus from security experts that these are the most likely.  
You should read about them and stay up to date on them because they make important security vulnerabilities that are likely to affect *your* organization more accessible, readable, and actionable.  
If you don't read about them, you stay in the dark on the most important and common vulnerabilities and be more easily breached as a result, losing the respect of your customers, ownership, and other important stakeholders.


* Injection - > Inject unauthorized or foreign code into a piece of software to get it to do something it was not otherwise authorized to perform. 

Metaphor: https://xkcd.com/327/

* Broken Authentication - > Injection flaws, such as SQL, NoSQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query. The attacker’s hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.

Metaphor: being able to use your neighbor's key to access your house.

* Sensitive Data Exposure - > Application functions related to authentication and session management are often implemented incorrectly, allowing attackers to compromise passwords, keys, or session tokens, or to exploit other implementation flaws to assume other users’ identities temporarily or permanently.

Metaphor: Caught with your pants down!

* XML External Entities (XXE) - > Many web applications and APIs do not properly protect sensitive data, such as financial, healthcare, and PII. Attackers may steal or modify such weakly protected data to conduct credit card fraud, identity theft, or other crimes. Sensitive data may be compromised without extra protection, such as encryption at rest or in transit, and requires special precautions when exchanged with the browser. 

Metaphor: Foreign saboteurs in the base!

* Security Misconfiguration - > Security misconfiguration is the most commonly seen issue. This is commonly a result of insecure default configurations, incomplete or ad hoc configurations, open cloud storage, misconfigured HTTP headers, and verbose error messages containing sensitive information. Not only must all operating systems, frameworks, libraries, and applications be securely configured, but they must be patched/upgraded in a timely fashion.

Metaphor: Electrician miswires the house (Could burn down or electrocute you)!

* Cross-Site Scripting (aka XSS) - > XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user-supplied data using a browser API that can create HTML or JavaScript. XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.

Metaphor: Alex Jones as your neighbors! https://www.youtube.com/watch?v=XRSg6MS5xqA

* Insecure Deserialization - ### >  Insecure deserialization often leads to remote code execution. Even if deserialization flaws do not result in remote code execution, they can be used to perform attacks, including replay attacks, injection attacks, and privilege escalation attacks.

(Marshaling, unmarshaling? stuff like that)

Metaphor: Someone taints your package en route (received an opened package from amazon!)

* Broken Access Control - ### > Restrictions on what authenticated users are allowed to do are often not properly enforced. Attackers can exploit these flaws to access unauthorized functionality and/or data, such as access to other users’ accounts, view sensitive files, modify other users’ data, change access rights, etc.

Metaphor: Bank robber can pretend to be you, and get the same access to your bank account! 

* Using components with known vulnerabilities - ### > Components, such as libraries, frameworks, and other software modules, run with the same privileges as the application. If a vulnerable component is exploited, such an attack can facilitate serious data loss or server takeover. Applications and APIs using components with known vulnerabilities may undermine application defenses and enable various attacks and impacts.

Metaphor: Using a broken condom.

* Insufficient logging and monitoring - ### >  Insufficient logging and monitoring, coupled with missing or ineffective integration with incident response, allows attackers to further attack systems, maintain persistence, pivot to more systems, and tamper, extract, or destroy data. Most breach studies show time to detect a breach is over 200 days, typically detected by external parties rather than internal processes or monitoring.

Metaphor: The robbers cleaned the bank out in the middle of the night, but because there weren't any cameras on-premises no suspects could be ID'd.




















