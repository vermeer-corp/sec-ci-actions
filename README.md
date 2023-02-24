# sec-ci-actions

Security-related composite actions used in Vermeer's CI pipeline

## Actions

### secret-scan

Scan for secrets such as API keys, passwords, etc. in the code

### secret-report

If secret-scan fails, comment on the PR with instructions for remediation and notify the security team for auditing purposes
