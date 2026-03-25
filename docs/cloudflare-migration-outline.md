# Cloudflare Migration Outline

## Pre-Migration
- Export and review current DNS
- Identify critical records
- Confirm mail-related records
- Review current registrar and nameserver setup
- Validate rollback approach

## Migration
- Recreate DNS in Cloudflare
- Confirm proxy choices per record
- Validate SSL/TLS posture
- Update nameservers
- Monitor propagation and service health

## Post-Migration
- Validate web, email, and API records
- Confirm no origin exposure issues
- Review caching/security settings
- Document final configuration
