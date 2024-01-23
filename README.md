# sec-ci-actions

Security-related composite actions used in Vermeer's CI pipeline

## Actions

### container-scan

Scan a container image for vulnerabilities

### iac-scan

Scan Infrastructure-as-Code files for configuration issues including Terraform, Kubernetes, Helm, etc.

### report-issue

Add a custom issue to the code compliance tracker

### secret-scan [DEPRECATED]

Scan for secrets such as API keys, passwords, etc. in the code

### secret-report [DEPRECATED]

If secret-scan fails, comment on the PR with instructions for remediation and notify the security team for auditing purposes
