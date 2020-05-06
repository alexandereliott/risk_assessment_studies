> quoted

* test

- [Heading](#heading)
  * [Sub-heading](#sub-heading)
    + [Sub-sub-heading](#sub-sub-heading)
- [Heading](#heading-1)
  * [Sub-heading](#sub-heading-1)
    + [Sub-sub-heading](#sub-sub-heading-1)
- [Heading](#heading-2)
  * [Sub-heading](#sub-heading-2)
    + [Sub-sub-heading](#sub-sub-heading-2)


# Heading levels

> This is a fixture to test heading levels

<!-- toc -->

## Heading

This is an h1 heading

### Sub-heading

This is an h2 heading

#### Sub-sub-heading

This is an h3 heading

## Heading

This is an h1 heading

### Sub-heading

This is an h2 heading

#### Sub-sub-heading

This is an h3 heading

## Heading

This is an h1 heading

### Sub-heading

This is an h2 heading

#### Sub-sub-heading

This is an h3 heading















Table of Contents
=================

   * [Risk Assessment](#risk-assessment)
      * [4 Main Risk Assessment Parameters of FAIR](#4-main-risk-assessment-parameters-of-fair)
         * [Other FAIR Definitions](#other-fair-definitions)
      * [Definitions of the OWASP Top 10](#definitions-of-the-owasp-top-10)
   * [* Injection - &gt; Inject unauthorized or foreign code into a piece of software to get it to do something it was not otherwise authorized to perform.](#-injection----inject-unauthorized-or-foreign-code-into-a-piece-of-software-to-get-it-to-do-something-it-was-not-otherwise-authorized-to-perform)
   * [* Broken Authentication - &gt; Injection flaws, such as SQL, NoSQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query. The attacker’s hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.](#-broken-authentication----injection-flaws-such-as-sql-nosql-os-and-ldap-injection-occur-when-untrusted-data-is-sent-to-an-interpreter-as-part-of-a-command-or-query-the-attackers-hostile-data-can-trick-the-interpreter-into-executing-unintended-commands-or-accessing-data-without-proper-authorization)
   * [* Sensitive Data Exposure - &gt; Application functions related to authentication and session management are often implemented incorrectly, allowing attackers to compromise passwords, keys, or session tokens, or to exploit other implementation flaws to assume other users’ identities temporarily or permanently.](#-sensitive-data-exposure----application-functions-related-to-authentication-and-session-management-are-often-implemented-incorrectly-allowing-attackers-to-compromise-passwords-keys-or-session-tokens-or-to-exploit-other-implementation-flaws-to-assume-other-users-identities-temporarily-or-permanently)
   * [* XML External Entities (XXE) - &gt; Many web applications and APIs do not properly protect sensitive data, such as financial, healthcare, and PII. Attackers may steal or modify such weakly protected data to conduct credit card fraud, identity theft, or other crimes. Sensitive data may be compromised without extra protection, such as encryption at rest or in transit, and requires special precautions when exchanged with the browser.](#-xml-external-entities-xxe----many-web-applications-and-apis-do-not-properly-protect-sensitive-data-such-as-financial-healthcare-and-pii-attackers-may-steal-or-modify-such-weakly-protected-data-to-conduct-credit-card-fraud-identity-theft-or-other-crimes-sensitive-data-may-be-compromised-without-extra-protection-such-as-encryption-at-rest-or-in-transit-and-requires-special-precautions-when-exchanged-with-the-browser)
   * [* Security Misconfiguration - &gt; Security misconfiguration is the most commonly seen issue. This is commonly a result of insecure default configurations, incomplete or ad hoc configurations, open cloud storage, misconfigured HTTP headers, and verbose error messages containing sensitive information. Not only must all operating systems, frameworks, libraries, and applications be securely configured, but they must be patched/upgraded in a timely fashion.](#-security-misconfiguration----security-misconfiguration-is-the-most-commonly-seen-issue-this-is-commonly-a-result-of-insecure-default-configurations-incomplete-or-ad-hoc-configurations-open-cloud-storage-misconfigured-http-headers-and-verbose-error-messages-containing-sensitive-information-not-only-must-all-operating-systems-frameworks-libraries-and-applications-be-securely-configured-but-they-must-be-patchedupgraded-in-a-timely-fashion)
   * [* Cross-Site Scripting (aka XSS) - &gt; XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user-supplied data using a browser API that can create HTML or JavaScript. XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.](#-cross-site-scripting-aka-xss----xss-flaws-occur-whenever-an-application-includes-untrusted-data-in-a-new-web-page-without-proper-validation-or-escaping-or-updates-an-existing-web-page-with-user-supplied-data-using-a-browser-api-that-can-create-html-or-javascript-xss-allows-attackers-to-execute-scripts-in-the-victims-browser-which-can-hijack-user-sessions-deface-web-sites-or-redirect-the-user-to-malicious-sites)
   * [* Insecure Deserialization - ### &gt;  Insecure deserialization often leads to remote code execution. Even if deserialization flaws do not result in remote code execution, they can be used to perform attacks, including replay attacks, injection attacks, and privilege escalation attacks.](#-insecure-deserialization------insecure-deserialization-often-leads-to-remote-code-execution-even-if-deserialization-flaws-do-not-result-in-remote-code-execution-they-can-be-used-to-perform-attacks-including-replay-attacks-injection-attacks-and-privilege-escalation-attacks)
   * [* Broken Access Control - ### &gt; Restrictions on what authenticated users are allowed to do are often not properly enforced. Attackers can exploit these flaws to access unauthorized functionality and/or data, such as access to other users’ accounts, view sensitive files, modify other users’ data, change access rights, etc.](#-broken-access-control-----restrictions-on-what-authenticated-users-are-allowed-to-do-are-often-not-properly-enforced-attackers-can-exploit-these-flaws-to-access-unauthorized-functionality-andor-data-such-as-access-to-other-users-accounts-view-sensitive-files-modify-other-users-data-change-access-rights-etc)
   * [* Using components with known vulnerabilities - ### &gt; Components, such as libraries, frameworks, and other software modules, run with the same privileges as the application. If a vulnerable component is exploited, such an attack can facilitate serious data loss or server takeover. Applications and APIs using components with known vulnerabilities may undermine application defenses and enable various attacks and impacts.](#-using-components-with-known-vulnerabilities-----components-such-as-libraries-frameworks-and-other-software-modules-run-with-the-same-privileges-as-the-application-if-a-vulnerable-component-is-exploited-such-an-attack-can-facilitate-serious-data-loss-or-server-takeover-applications-and-apis-using-components-with-known-vulnerabilities-may-undermine-application-defenses-and-enable-various-attacks-and-impacts)
   * [* Insufficient logging and monitoring - ### &gt;  Insufficient logging and monitoring, coupled with missing or ineffective integration with incident response, allows attackers to further attack systems, maintain persistence, pivot to more systems, and tamper, extract, or destroy data. Most breach studies show time to detect a breach is over 200 days, typically detected by external parties rather than internal processes or monitoring.](#-insufficient-logging-and-monitoring------insufficient-logging-and-monitoring-coupled-with-missing-or-ineffective-integration-with-incident-response-allows-attackers-to-further-attack-systems-maintain-persistence-pivot-to-more-systems-and-tamper-extract-or-destroy-data-most-breach-studies-show-time-to-detect-a-breach-is-over-200-days-typically-detected-by-external-parties-rather-than-internal-processes-or-monitoring)
