# Outage Triage Checklist

## First 15 Minutes
- Confirm incident is real
- Capture timestamp and symptoms
- Check DNS resolution
- Check Cloudflare status and configuration changes
- Check origin health
- Check monitoring dashboards
- Identify blast radius
- Assign incident owner

## Rule Out
- DNS misconfiguration
- expired certificate
- origin outage
- WAF/rate limiting block
- bad deployment
- third-party dependency failure

## Immediate Outputs
- Severity level
- probable fault domain
- next action owner
- stakeholder update timeline
