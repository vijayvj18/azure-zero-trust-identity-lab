# Incident Scenarios

## Scenario 1: High-risk sign-in blocked

- User: `alice.user@<tenant>`
- Trigger: Sign-in from unusual location/device (detected as high risk).
- Control: Conditional Access policy `CA02 - Block high-risk sign-ins`.
- Result: Sign-in blocked automatically.
- Investigation steps:
  1. Go to Entra → Protection → Risky sign-ins.
  2. Filter for Alice.
  3. Review sign-in details (location, IP, device).
  4. Decide whether to confirm user compromise or dismiss user risk.
