# JML Lifecycle – SailPoint IdentityIQ

## Objective

This is a hands-on learning project demonstrating Joiner, Mover and Leaver lifecycle processes in SailPoint IdentityIQ.

## 1. Joiner

When a new employee joins the organization:

1. Employee data is received from the authoritative source.
2. SailPoint performs aggregation.
3. Identity correlation is performed.
4. The identity is created or updated in the Identity Cube.
5. Lifecycle events, roles and policies are evaluated.
6. A provisioning plan is generated.
7. Required accounts and entitlements are provisioned to target applications.

## 2. Mover

When an employee changes department or job role:

1. Employee information is updated in the authoritative source.
2. SailPoint aggregates the updated information.
3. Identity attributes are refreshed.
4. Old access is identified for removal.
5. New access is identified based on the new role.
6. A provisioning plan is generated.
7. Required access is revoked and new access is provisioned.

## 3. Leaver

When an employee leaves the organization:

1. Employee status is updated in the authoritative source.
2. SailPoint detects the lifecycle change.
3. User accounts and entitlements are identified.
4. Deprovisioning actions are generated.
5. Accounts may be disabled or deleted based on configuration.
6. User access is revoked from target applications.

## Key SailPoint Components

- Aggregation
- Identity Correlation
- Identity Refresh
- Lifecycle Events
- Provisioning Plan
- Provisioning
- Deprovisioning
- Roles and Entitlements
- Access Policies

## Note

This is a hands-on learning/demo project created to demonstrate understanding of SailPoint IdentityIQ IAM lifecycle processes.
