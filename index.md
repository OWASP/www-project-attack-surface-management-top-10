---

layout: col-sidebar
title: OWASP Attack Surface Management Top 10
tags: example-tag
level: 2
type: documentation
pitch: A very brief, one-line description of your project

---

* Introduction
    The OWASP ASM (Attack Surface Management) Top 10 is a community-driven project that identifies the most critical risks associated with external attack surfaces. While OWASP has historically focused on web application security (OWASP Web Top 10) and API security (OWASP API Security Top 10), modern apps extend beyond traditional infrastrucures and boundaries, third-party SaaS applications, exposed APIs, and forgotten assets.

    
With organizations increasingly shifting to cloud-native architectures and expanding their digital footprint, security teams struggle to track, assess, and mitigate risks associated with externally exposed assets. The OWASP ASM Top 10 aims to bridge this gap by providing a structured risk framework for external attack surface exposures.

* How ASM Relates to Web Security & Traditional OWASP Projects
    OWASP’s foundational projects, like OWASP Web Security Top 10 and API Security Top 10, focus primarily on securing known and controlled application environments. However, organizations today operate in a world where:

* Web applications and APIs are interconnected with third-party services, cloud environments, and SaaS tools.
* Security perimeters have become more complex, with assets dynamically appearing and disappearing.
* Threat actors actively perform reconnaissance on external attack surfaces before launching targeted attacks.

ASM and Web Security: The Missing Link

* The OWASP Web Security Top 10 primarily focuses on vulnerabilities within applications (e.g., SQL Injection, XSS, Broken Access Control).
* The OWASP API Security Top 10 tackles risks related to API authentication, authorization, and data exposure.
* However, neither project addresses the broader risk of asset discovery, external exposure, or attack surface visibility; which is where ASM becomes critical.

    
For example, an organization may secure its main web application, but if it has forgotten subdomains running outdated software or exposed misconfigured APIs, attackers can exploit these weaknesses. The OWASP ASM Top 10 will help organizations understand and mitigate these risks before they become an entry point for attackers.

* Why This Project is Critical for Modern Security
    Security teams increasingly adopt Attack Surface Management (ASM) platforms to gain visibility into external-facing risks, but there is no standardized framework for prioritizing these risks. The OWASP ASM Top 10 will serve as a benchmark for assessing, categorizing, and mitigating external attack surface threats, ensuring alignment with modern security strategies.

Key Benefits:

* Enhances OWASP’s Web Security Efforts by providing a risk-based approach to external exposure.
* Aligns with ASM Industry Trends, ensuring organizations can systematically identify and address external risks.
* Provides a Standardized Framework for security teams, vendors, and regulators to prioritize attack surface risks.

This project aims to empower security teams with actionable insights, risk categorization, and remediation strategies to improve external risk visibility and attack surface hygiene.

* ASM Top 10: The OWASP ASM Top 10 categorizes the most impactful external attack surface risks, including:

* Unmanaged & Unknown External Assets
* Shadow IT, forgotten subdomains, untracked cloud resources, and legacy applications expanding the attack surface.
* Exposed APIs & Unprotected Endpoints
* Publicly accessible APIs, missing authentication, excessive permissions, and API abuse vectors.
* Public Code & Credential Exposure
* Leaked API keys, hardcoded secrets in mobile apps, public GitHub repositories, and exposed configuration files.
* Fake Domains & Impersonation Attacks
* Typosquatting, phishing domains, fake mobile apps, and brand impersonation threats.
* Third-Party SaaS & Shadow IT Risks
* Untracked SaaS applications, exposed Postman collections, and unauthorized cloud services storing sensitive data.
* Cloud & SaaS Misconfigurations
* Publicly exposed cloud storage, misconfigured IAM permissions, unsecured file-sharing links, and weak authentication in SaaS applications.
* Exposed Debug & Test Environments
* Publicly accessible staging environments, development servers, and leftover testing infrastructure.
* Insecure DNS Configurations & Domain Hijacking
* Dangling DNS records, misconfigured MX/NS records, and hijackable subdomains leading to takeovers.
* Unauthenticated Resources Accessible on the Internet
* Publicly exposed admin panels, storage buckets, CI/CD pipelines, monitoring dashboards, and logs.
* Lack of Continuous Attack Surface Monitoring
* Failure to detect newly exposed assets, missing automated inventory tracking, and weak external risk monitoring.

* How will this project benefit the security community?
* Security Practitioners: Provides a risk prioritization framework to reduce external exposure.
* Developers & DevOps Teams: Raises awareness of common misconfigurations in APIs, cloud environments, and CI/CD pipelines.
* CISOs & Security Leaders: Helps define external risk reduction strategies and align with security best practices.
* Researchers & Penetration Testers: Offers insights into real-world attack vectors used for reconnaissance and initial compromise.

### Road Map
Phase 1 (0-3 months): Project Initiation:

* Draft initial OWASP ASM Top 10 list
* Gather contributors and community feedback
* Define criteria for risk classification

Phase 2 (3-6 months): Research & Documentation:

* Collect real-world examples and case studies
* Define risk assessment methodology
* Draft best practices and mitigation techniques

Phase 3 (6-12 months): Public Release & Community Engagement:

* Publish v1.0 of OWASP ASM Top 10
* Gather feedback and iterate
* Present findings at security conferences, webinars, and OWASP events

Ongoing (After 12 months)

* Maintain and update the list based on evolving threats
* Collaborate with other OWASP projects (e.g., OWASP Amass, OWASP API Security Top 10)
* Publish periodic industry reports on ASM trends
