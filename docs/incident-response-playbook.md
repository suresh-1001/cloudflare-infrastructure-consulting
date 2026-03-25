# Incident Response Playbook

## Objective
Provide a practical response model for outages, degradation, and Cloudflare-related incidents.

## Response Flow
1. Detect incident
2. Confirm scope and severity
3. Identify whether issue is DNS, Cloudflare edge, origin, app, or third-party dependency
4. Contain impact where possible
5. Restore service
6. Validate recovery
7. Communicate status
8. Perform post-incident review

## Initial Triage Questions
- Is the site fully down or partially degraded?
- Is DNS resolving correctly?
- Is Cloudflare serving errors or timing out to origin?
- Is the origin healthy?
- Are alerts firing from multiple sources or only one?
- Is the issue global or location-specific?

## Communication
- Internal technical update
- Business stakeholder update
- Customer-facing update if needed

## Recovery Validation
- DNS resolves correctly
- Website returns expected HTTP responses
- Critical user journeys function
- Monitoring is green
- Error rates return to baseline
