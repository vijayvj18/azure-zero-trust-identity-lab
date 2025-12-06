# Users and Groups

## Users

- `alice.user@<tenant>` - Standard user
- `bob.user@<tenant>` - Potential privileged admin

## Groups

- `grp-zero-trust-standard-users`
  - Members: Alice
  - Purpose: Non-privileged day-to-day users.

- `grp-zero-trust-privileged-admins`
  - Members: Bob
  - Purpose: Users who can obtain privileged roles via PIM (Just-in-Time).
