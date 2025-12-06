# Defender / Identity Alerts

## Alert 1

- Type: Multiple failed sign-in attempts
- Affected user: `alice.user@<tenant>`
- Source: Entra ID / Identity Protection → surfaced in Defender
- Response steps:
  1. Confirm if user behavior is legitimate.
  2. Check sign-in locations and IP addresses.
  3. If suspicious, reset password and require re-registration of MFA.
