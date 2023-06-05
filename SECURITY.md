# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.







# JONATHAN SECURITY UPDATES


## 1. Adding new AWS services to improve security:

* AWS WAF (Web Application Firewall): This can be added to the ELB (Elastic Load Balancer) to protect some application from common web exploits that could affect availability, compromise security, or consume excessive resources.

* AWS Shield: This provides DDoS protection and can be used in conjunction with AWS WAF for comprehensive security.

* AWS IAM (Identity and Access Management): IAM can be used to manage access to AWS services and resources securely. It allows  to create and manage AWS users and groups and use permissions to allow and deny their access to AWS resources.

* AWS Secrets Manager: This can be used to rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. This can help protect access to applications, services, and IT resources without the upfront investment and on-going maintenance costs of operating your own infrastructure.

* AWS GuardDuty: This is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts and workloads. With the cloud, the collection and aggregation of account and network activities is simplified, but it can be time consuming for security teams to continuously analyze event log data for potential threats. GuardDuty can handle this by detecting a wide variety of threats, including unusual API calls or potentially unauthorized deployments that indicate a possible account compromise.

* AWS CloudTrail: This service provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command line tools, and other AWS services. This event history simplifies security analysis, resource change tracking, and troubleshooting. In addition, you can use CloudTrail to detect unusual activity in your AWS accounts. These capabilities help simplify operational analysis and troubleshooting.

* AWS Config: This service enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations.

* AWS Macie: This is a security service that uses machine learning to automatically discover, classify, and protect sensitive data like Personally Identifiable Information (PII). Macie recognizes sensitive data such as PII, details of API calls and security configuration settings, and provides dashboards and alerts that give visibility into how this data is being accessed or moved.

* AWS Inspector: This is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. AWS Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. After performing an assessment, AWS Inspector produces a detailed list of security findings prioritized by level of severity. These findings can be reviewed directly or as part of detailed assessment reports which are available via the AWS Inspector console or API.

* AWS Security Hub: This gives you a comprehensive view of your high-priority security alerts and compliance status across AWS accounts. There are a range of powerful security tools at your disposal, like AWS Inspector, GuardDuty, and Macie, and AWS Security Hub brings all of their findings together in one place. It can also integrate with other popular security tools like Splunk, PagerDuty, and Trend Micro.

* IMPORTANT: By using AWS Security Hub, we can run automated, continuous compliance checks based on industry standards and best practices, such as the Center for Internet Security (CIS) AWS Foundations Benchmark. This helps ensure that AWS accounts are following security best practices.




## 2. Security related policies for DevOps and Developers:

* Principle of Least Privilege (PoLP): Each user should have the minimum levels of access necessary to perform their job functions. This can be managed through IAM policies.

* Regular Audits: Regular audits should be conducted to ensure compliance with security policies and to detect any anomalies.

* Change Management: All changes to the production environment should be logged and monitored. This includes tracking who made the change, what the change was, when it was made, and why it was necessary.

* Multi-Factor Authentication (MFA): Enforce MFA for all users to add an extra layer of security.




## 3. Security issues if a team member leaves:

When a team member leaves the company, there is always a risk of security issues if proper offboarding procedures are not followed. Here are some steps to mitigate these risks:

* Access Revocation: As soon as a team member leaves, their access to all systems and data should be immediately revoked. This includes access to the AWS console, servers, databases, source code, third-party tools, email, and any other systems they had access to.

* Key Rotation: If the team member had access to any keys or secrets, these should be rotated. This includes AWS access keys, database passwords, API keys, etc.

* Audit: Conduct an audit of all actions taken by the team member in the period leading up to their departure. This can help identify any potential issues or malicious actions.




## 4. In case of a hacker or disgruntled employee:

In the event of a security breach, whether it's from an external hacker or a disgruntled employee, there are several steps that should be taken:

* Incident Response Plan: Have a well-defined incident response plan in place. This should outline the steps to take in the event of a security breach, including identifying the breach, containing the damage, eradicating the threat, recovering from the incident, and conducting a post-incident analysis.

* Backup and Disaster Recovery: Regular backups should be taken and a disaster recovery plan should be in place. This will allow you to restore your systems to a state before the breach occurred.

* Monitoring and Alerting: Implement monitoring and alerting on your systems. This can help you detect a breach as soon as it happens and take immediate action.

* Least Privilege Access: Follow the principle of least privilege. Each user should only have the access they need to perform their job and nothing more. This can limit the damage a single user can do.

* Separation of Duties: Implement separation of duties. This means that no single individual should have control over all parts of a critical process or system.

Security is not a one-time thing but an ongoing process. Regular audits, training, and updates to security policies and procedures are essential.



