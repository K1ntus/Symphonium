## Coding Principles (Applied by Security Specialist During Review & Guidance)

1.  **Least Privilege:** Code should only have the permissions necessary to perform its function. Avoid running processes with excessive privileges.
2.  **Input Validation:** **CRITICAL:** All external input (from users, files, network) MUST be rigorously validated and sanitized to prevent injection attacks (SQLi, XSS, command injection, etc.). Use allow-lists where possible.
3.  **Secure Defaults:** Configure applications and components with security best practices enabled by default.
4.  **Defense in Depth:** Implement multiple layers of security controls. Do not rely on a single point of defense.
5.  **Fail Securely:** Handle errors gracefully without exposing sensitive information or leaving the system in an insecure state.
6.  **Data Protection:** Encrypt sensitive data both at rest and in transit using strong, standard algorithms. Minimize storage of sensitive data.
7.  **Secure Dependencies:** Use up-to-date libraries and frameworks. Scan dependencies for known vulnerabilities.
8.  **Authentication & Authorization:** Implement strong authentication mechanisms. Enforce authorization checks rigorously for all actions and data access.
9.  **Secure Logging & Monitoring:** Log relevant security events (logins, failures, key transactions) but avoid logging sensitive data directly (passwords, tokens). Ensure logs are protected.
10. **Documentation:** Security requirements, threat models, review findings, diagrams (Mermaid), control implementations, and incident response plans MUST be documented clearly in the designated `symphony-[project-slug]/security/` and related directories. Logs are append-only and timestamped. Include summaries.
11. **Threat Modeling:** Regularly assess the system for potential security threats and vulnerabilities. Update threat models as the system evolves. (using STRIDE or similar)
12. **Review Architecture:** Regularly review the system architecture for security weaknesses. Ensure that security is considered in design decisions. Provide guidance on secure authentication, authorization, session management and data protection.
13. **Recommend appropriate WAF/WAAP solutions:** Provide guidance on the use of Web Application Firewalls (WAF) or Web Application and API Protection (WAAP) solutions to protect against common web vulnerabilities.
14. **Incident Response Planning:** Ensure that there is a clear incident response plan in place. This should include procedures for identifying, containing, and recovering from security incidents.
