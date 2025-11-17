# Generate Audit Report Command

Create a comprehensive compliance audit report for the current project.

## Report Structure

### 1. Executive Summary
- Overall compliance status
- Critical findings count
- High-priority recommendations
- Compliance score (if applicable)

### 2. Scope & Methodology
- Files and directories audited
- Compliance frameworks evaluated against
- Audit timestamp and version

### 3. Detailed Findings

For each finding, include:
- **Finding ID**: Unique identifier (e.g., COMP-001)
- **Severity**: Critical / High / Medium / Low
- **Category**: Security, Privacy, Data Handling, Documentation
- **Location**: File path and line numbers
- **Description**: What the issue is
- **Impact**: Potential compliance or security impact
- **Recommendation**: Specific steps to remediate
- **Standard Reference**: Which compliance standard this relates to

### 4. Compliance Matrix

Create a table showing:
- Requirement area
- Current status (Compliant / Partial / Non-Compliant)
- Evidence or gaps
- Action items

### 5. Recommendations

Prioritized list of remediation actions:
1. Immediate actions (critical issues)
2. Short-term improvements (high priority)
3. Long-term enhancements (medium priority)

### 6. Appendix
- Glossary of compliance terms
- References to standards and regulations
- Audit methodology details

## Output Format

Generate the report as a Markdown document that can be:
- Saved to `compliance-audit-report.md`
- Converted to PDF for stakeholder review
- Tracked in version control for compliance history

## Best Practices

- Use clear, non-technical language for executive summary
- Provide specific, actionable recommendations
- Include code snippets showing both the issue and the fix
- Reference specific compliance standard sections
- Include a risk assessment for each finding
