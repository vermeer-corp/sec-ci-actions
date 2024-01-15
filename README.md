# sec-ci-actions

Security-related composite actions used in Vermeer's CI pipeline

## Actions

### dotnet-sca-scan

Scan a .NET project's top-level and transitive packages for vulnerabilities

### dotnet-sca-report

If dotnet-sca-scan fails, comment on the PR with instructions for remediation

### report-issue

Add a custom issue to the code compliance tracker

### secret-scan [DEPRECATED]

Scan for secrets such as API keys, passwords, etc. in the code

### secret-report [DEPRECATED]

If secret-scan fails, comment on the PR with instructions for remediation and notify the security team for auditing purposes
