# Cloudflare Review Checklist

## DNS and Proxy
- Confirm authoritative nameservers
- Review DNS record accuracy
- Validate proxied vs DNS-only records
- Confirm origin exposure is minimized
- Review TTL strategy where applicable

## SSL/TLS
- Confirm SSL mode is correct
- Review certificate coverage
- Validate origin certificate posture
- Review HTTPS enforcement settings

## Edge Security
- Review WAF configuration
- Review rate limiting posture
- Review bot protection settings
- Confirm admin and sensitive paths are protected

## Caching and Performance
- Review cache settings and bypass logic
- Review static asset handling
- Identify unnecessary edge complexity
- Confirm there are no conflicting rules

## Reliability
- Review origin dependency risks
- Review failover approach
- Review monitoring gaps
- Confirm incident ownership and escalation path
