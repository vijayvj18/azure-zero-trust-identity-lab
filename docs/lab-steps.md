# Azure Zero Trust Identity Lab - Runbook

## Phase 0 - Setup
- Created `rg-zero-trust-lab` resource group.

## Phase 1 - Users and Groups
- Created users: Alice (standard), Bob (potential admin).
- Created groups for standard and privileged users.

## Phase 2 - CA01 Require MFA
- Policy CA01 to require MFA for grp-zero-trust-standard-users.

## Phase 3 - CA02 Block high-risk sign-ins
- Policy CA02 blocks high-risk sign-ins for standard users.

## Phase 4 - PIM
- Configured PIM for Security Administrator role.
- Bob is eligible, must activate via MFA + justification.

## Phase 5 - Defender
- Enabled Defender.
- Observed identity-related alerts and wrote response steps.
