# Incident Severity Matrix

## Document Information

| Item | Details |
|------|---------|
| Document Name | Incident Severity Matrix |
| Version | 1.0 |
| Effective Date | July 2026 |
| Review Frequency | Annual |
| Applies To | IT Staff, Incident Response Team, Management |

---

# Purpose

The Incident Severity Matrix provides a standardized method for classifying cybersecurity incidents based on their business impact, operational disruption, data sensitivity, and urgency. Proper classification ensures that incidents receive the appropriate level of attention, resources, and escalation.

---

# Scope

This matrix applies to all cybersecurity incidents, including:

- Malware infections
- Ransomware attacks
- Phishing incidents
- Data breaches
- Unauthorized access
- Denial-of-Service (DoS) attacks
- Insider threats
- Lost or stolen devices
- Cloud security incidents
- Physical security incidents affecting IT assets

---

# Severity Levels

The organization classifies incidents into four severity levels:

| Severity | Description | Required Response Time |
|----------|-------------|------------------------|
| Critical (Level 1) | Severe impact on business operations or major data compromise | Immediate (within 15 minutes) |
| High (Level 2) | Significant impact requiring urgent response | Within 1 hour |
| Medium (Level 3) | Moderate impact with limited business disruption | Within 4 hours |
| Low (Level 4) | Minor security event with minimal impact | Within 1 business day |

---

# Severity Criteria

## Level 1 – Critical

### Characteristics

- Major business disruption
- Widespread system outage
- Large-scale data breach
- Active ransomware infection
- Critical servers unavailable
- Significant financial or legal impact
- Public-facing services unavailable
- Multiple departments affected

### Examples

- Customer database compromised
- Enterprise-wide ransomware attack
- Domain administrator account compromised
- Major cloud service compromise
- Critical server failure caused by cyberattack

### Response

- Activate Incident Response Team immediately.
- Notify executive management.
- Isolate affected systems.
- Preserve forensic evidence.
- Begin containment without delay.
- Consider notifying legal counsel and regulatory authorities if required.

---

## Level 2 – High

### Characteristics

- Significant operational impact
- Sensitive data exposed
- Multiple users affected
- Critical application unavailable
- High likelihood of business disruption

### Examples

- HR records accessed without authorization
- Malware infection on a production server
- Successful phishing attack involving employee credentials
- Unauthorized administrator login
- Cloud account compromise

### Response

- Notify IT Administrator immediately.
- Begin containment within one hour.
- Investigate affected systems.
- Reset compromised credentials.
- Monitor for additional suspicious activity.

---

## Level 3 – Medium

### Characteristics

- Limited operational impact
- Single department affected
- No confirmed sensitive data loss
- Localized malware infection
- Recoverable using standard procedures

### Examples

- Malware detected on one workstation
- Employee clicked a phishing link but credentials were not entered
- Unauthorized USB device detected
- Firewall alert requiring investigation
- Temporary application outage

### Response

- Assign incident to the IT team.
- Investigate the cause.
- Remove malicious files if present.
- Restore affected systems.
- Document the incident.

---

## Level 4 – Low

### Characteristics

- Minimal business impact
- No service interruption
- No confirmed compromise
- Prevented by existing security controls

### Examples

- Spam email blocked
- Antivirus blocked a malicious file
- Failed login attempts
- Policy violation without security impact
- Routine security alert

### Response

- Record the event.
- Monitor for repeated activity.
- Notify the user if necessary.
- Close the incident after review.

---

# Incident Classification Factors

When determining severity, consider:

- Number of affected systems
- Number of affected users
- Business impact
- Financial impact
- Data sensitivity
- Regulatory impact
- Service availability
- Recovery time
- Likelihood of ongoing attack
- Public or customer impact

---

# Escalation Matrix

| Severity | IT Administrator | Management | Incident Response Team | Legal | External Authorities |
|----------|------------------|------------|------------------------|-------|----------------------|
| Critical | Immediate | Immediate | Activated | If Required | If Required |
| High | Immediate | Yes | Activated | If Required | If Required |
| Medium | Yes | Optional | As Needed | No | No |
| Low | Yes | No | Not Required | No | No |

---

# Communication Requirements

## Critical

Notify:

- Executive Management
- IT Administrator
- Incident Response Team
- Department Managers
- Legal Advisor (if required)
- Regulatory Authorities (if applicable)

---

## High

Notify:

- IT Administrator
- Management
- Department Managers
- Incident Response Team

---

## Medium

Notify:

- IT Administrator
- Department Manager

---

## Low

Notify:

- IT Administrator (for documentation)

---

# Response Priorities

During every incident, responders should prioritize:

1. Protect human safety.
2. Prevent further damage.
3. Preserve evidence.
4. Restore critical business operations.
5. Recover affected systems.
6. Document all response activities.
7. Conduct a post-incident review.

---

# Documentation Requirements

Every incident should include:

- Incident ID
- Date and time
- Reporter
- Severity level
- Description
- Affected systems
- Impact assessment
- Response actions
- Recovery activities
- Root cause
- Lessons learned

---

# Review Process

Severity classifications should be reviewed:

- During the initial investigation.
- Whenever new evidence becomes available.
- Before incident closure.
- During the post-incident review.

If the impact changes, the severity level should be updated accordingly.

---

# Integration with Other Documents

This matrix supports:

- Incident Response Playbook
- Ransomware Response Playbook
- Malware Response Playbook
- Phishing Response Playbook
- Data Breach Response Playbook
- Business Continuity Plan
- Disaster Recovery Plan

---

# Policy Review

This document shall be reviewed:

- Every 12 months.
- After major cybersecurity incidents.
- Following infrastructure changes.
- When organizational risk levels change.

---

# Version History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | July 2026 | Initial Release |

---

# Approval

| Approved By | Date |
|-------------|------|
| Business Owner | __________ |
| IT Administrator | __________ |

---

# Conclusion

The Incident Severity Matrix provides a consistent framework for evaluating cybersecurity incidents based on their impact and urgency. Using standardized severity levels enables faster decision-making, appropriate resource allocation, effective communication, and a coordinated response to security events across the organization.
