# Audit Compliance Command

You are performing a regulatory compliance audit of the codebase. Follow these steps:

## Audit Scope

1. **Security & Privacy**
   - Check for PII handling and anonymization
   - Verify encryption is used for sensitive data (AES-256 or better)
   - Ensure audit logging is in place for all data access
   - Review authentication and authorization mechanisms

2. **Data Handling**
   - Identify all locations where sensitive data is processed
   - Verify data retention policies are implemented
   - Check for proper input validation and sanitization
   - Review database query security (SQL injection prevention)

3. **Compliance Standards**
   - FISMA compliance requirements
   - FedRAMP compliance requirements
   - Industry-specific regulations (e.g., mortgage servicing regulations)
   - Review code comments for compliance annotations

4. **Documentation**
   - Verify all compliance-critical functions are documented
   - Check for security assumptions documented in code
   - Review API documentation for security warnings

## Output Format

Generate a structured audit report with:
- **Critical Issues**: Security vulnerabilities or compliance violations
- **Warnings**: Potential compliance concerns requiring review
- **Recommendations**: Best practices to improve compliance posture
- **Compliant Sections**: Areas that meet compliance requirements

## Deliverable

Present findings in a clear, actionable format with:
- File paths and line numbers for each issue
- Specific remediation steps
- Priority levels (Critical, High, Medium, Low)
- References to relevant compliance standards
