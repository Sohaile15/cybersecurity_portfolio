Security Controls Assessment — Final Report

1. Executive Summary

This report presents a simulated Governance, Risk and Compliance (GRC) assessment for GulfTech Solutions, a fictional UAE-based IT services company.

The assessment covers ISO/IEC 27001:2022, NIST Cybersecurity Framework (CSF) 2.0, and the NIST Risk Management Framework (RMF).

The objective is to identify example security risks, document evidence requirements, assess potential control gaps, and recommend risk-reduction measures.

Disclaimer: This is an educational case study. No real organisation was assessed, and no formal audit or certification is claimed.

2. Scope and Objectives

The simulated assessment covers:

* Employee accounts and authentication
* Client document access
* Backup and recovery
* Security monitoring
* Incident response
* Employee awareness
* Third-party suppliers
* Governance and risk ownership

The objectives are to identify risks, map relevant controls, document improvement opportunities, and recommend remediation actions.

3. Methodology

Likelihood and impact are each scored from 1 to 5.

Risk Score = Likelihood x Impact

The scoring thresholds in the accompanying risk register are illustrative project assumptions, not mandatory ISO 27001 or NIST thresholds.

Where evidence is unavailable, the assessment records that evidence is required. Missing evidence alone does not prove that a control is ineffective.

4. Summary of Example Risks

Risk R-01: Employee Account Compromise

Scenario: An attacker gains access to an employee account.

Potential impact: Unauthorised access to company systems and client documents.

Recommended treatment: Verify multi-factor authentication (MFA) coverage and review privileged accounts.

Risk R-02: Excessive Access Permissions

Scenario: Employees retain access to client documents they no longer need.

Potential impact: Unauthorised disclosure of confidential information.

Recommended treatment: Apply least privilege and perform periodic access reviews.

Risk R-03: Backup and Recovery Failure

Scenario: Critical information cannot be restored following deletion or ransomware.

Potential impact: Data loss and business interruption.

Recommended treatment: Verify backup coverage and perform documented restoration tests.

Risk R-04: Insufficient Security Monitoring

Scenario: Suspicious activity is not detected promptly.

Potential impact: An attacker may remain undetected for longer.

Recommended treatment: Define critical log sources, alert ownership, and escalation procedures.

Risk R-05: Incident Response Gaps

Scenario: Security incidents are handled inconsistently.

Potential impact: Delayed containment and recovery.

Recommended treatment: Document response responsibilities and conduct tabletop exercises.

Risk R-06: Phishing and Social Engineering

Scenario: An employee follows a malicious link or discloses credentials.

Potential impact: Account compromise or malware infection.

Recommended treatment: Provide security awareness training and establish a phishing-reporting process.

Risk R-07: Third-Party Supplier Risk

Scenario: A supplier security incident affects company services or data.

Potential impact: Service disruption or information exposure.

Recommended treatment: Assess critical suppliers and review contractual security requirements.

Note: These are simulated risk scenarios, not confirmed incidents or audit findings.

5. ISO/IEC 27001:2022 Control Assessment

The control assessment workbook covers selected areas such as access control, identity management, authentication, backups, logging, incident management, awareness, and supplier relationships.

Each assessment entry documents the control reference, assessment objective, scenario assumptions, evidence requirements, associated risk, identified information gaps, and recommended remediation.

Where sufficient evidence is unavailable, the status is recorded as “Not assessed — evidence required”.

Control applicability must be evaluated against the organisation’s scope, risk treatment process, and Statement of Applicability.

6. NIST CSF 2.0 Gap Assessment

The assessment uses the six NIST CSF functions:

* Govern: Establish cybersecurity responsibilities and risk oversight.
* Identify: Understand assets, data, and cybersecurity risks.
* Protect: Implement safeguards such as access management and data protection.
* Detect: Identify potentially harmful cybersecurity events.
* Respond: Manage and contain cybersecurity incidents.
* Recover: Restore affected systems and services.

The accompanying workbook describes simulated current states, target outcomes, identified gaps, and proposed improvements.

7. NIST Risk Management Framework

The RMF lifecycle documentation describes seven steps:

1. Prepare — establish context and responsibilities.
2. Categorize — determine the impact of potential information loss or disruption.
3. Select — identify appropriate security and privacy controls.
4. Implement — put selected controls into operation.
5. Assess — evaluate control implementation and effectiveness.
6. Authorize — obtain a risk-based decision from the authorised official.
7. Monitor — track security posture, changes, and emerging risks.

The project documents proposed activities and outputs. It does not claim that a real system was categorised, assessed, or authorised.

8. Recommended Priorities

The proposed priorities for the fictional scenario are:

1. Confirm system scope, governance, and risk ownership.
2. Review authentication, privileged accounts, and access permissions.
3. Validate backup coverage and restoration capability.
4. Establish security monitoring and incident escalation.
5. Review supplier risks and employee awareness.
6. Assign remediation owners, target dates, and evidence requirements.

These priorities would require validation by actual business and risk owners in a real assessment.

9. Limitations

* The organisation and scenarios are fictional.
* Current-state descriptions are simulated assumptions.
* No real interviews, technical tests, or audit evidence were collected.
* Risk ratings and priorities are illustrative.
* Framework mappings require validation against actual organisational requirements.
* This project does not establish formal compliance or certification.

10. Conclusion

This case study demonstrates a structured approach to cybersecurity risk documentation, control mapping, gap analysis, and remediation planning.

A real assessment would require validated evidence, stakeholder input, approved risk criteria, control testing where appropriate, and decisions by authorised risk owners.

References

* ISO/IEC 27001:2022 — Information security management systems — Requirements.
* NIST Cybersecurity Framework 2.0: https://www.nist.gov/cyberframework
* NIST RMF Courses: https://csrc.nist.gov/Projects/risk-management/rmf-courses
* NIST SP 800-37 Rev. 2 — Risk Management Framework for Information Systems and Organizations.
