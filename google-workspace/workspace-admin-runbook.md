# Google Workspace Administration Runbook

## Purpose
This runbook documents standard administrative workflows for a small organisation using Google Workspace. It is a learning/portfolio artefact, not a record of production administration.

## Core concepts
- Admin console: central control panel for users, groups, devices, and policies
- User lifecycle: onboarding, changes, offboarding
- Organisational units: groups of users with shared settings
- Groups: managed access to resources and email distribution
- Shared Drives: team-owned storage with controlled access
- Security: 2-step verification, session controls, password policies, recovery

## New starter workflow
1. Confirm approved request and required access.
2. Create the user account in the Admin console.
3. Assign the user to the appropriate organisational unit.
4. Add the user to required Google Groups.
5. Grant access only to required Shared Drives.
6. Share welcome information and password-reset guidance.
7. Record the account creation in the access log.

## Leaver workflow
1. Confirm the departure date and manager approval.
2. Remove group memberships and Shared Drive access.
3. Suspend or delete the account according to company policy.
4. Transfer or archive required Drive content.
5. Revoke sessions and reset credentials where appropriate.
6. Record the change in the access log.

## Common requests
| Request | Initial action | Escalation |
|---|---|---|
| Password reset | Verify identity and follow reset procedure | Super admin if locked out |
| Shared Drive access | Confirm business need and manager approval | Security review for sensitive data |
| Calendar access | Add user to appropriate calendar/group | Admin if policy conflict |
| Suspicious login | Advise password change and 2SV review | Security/admin escalation |

## Security principles
- Grant least privilege.
- Use groups rather than individual permissions where possible.
- Remove access promptly after departure.
- Do not share admin credentials.
- Document all access changes.
