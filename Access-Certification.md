# Access Certification – SailPoint IdentityIQ

## Objective

This document demonstrates the Access Certification process in SailPoint IdentityIQ. Access Certification helps organizations review and validate user access on a regular basis.

## 1. Certification Campaign

A certification campaign is created to review user accounts, roles and entitlements.

Example:

A manager receives a certification task to review the access of employees in their team.

## 2. Certification Items

The reviewer may see:

- User identity
- Application accounts
- Roles
- Entitlements
- Access details
- Previous certification decisions

## 3. Reviewer Actions

The reviewer can typically:

- Approve access
- Revoke access
- Request additional information
- Reassign the review when permitted by configuration

## 4. Certification Flow

Certification Campaign Created  
↓  
Certification Items Generated  
↓  
Reviewer Receives Certification  
↓  
Access Reviewed  
↓  
Approve / Revoke  
↓  
Revocation Provisioned to Target System  
↓  
Certification Completed

## 5. Example Scenario

An employee has access to a Finance application.

During the quarterly access review, the employee's manager determines that the Finance access is no longer required.

The manager revokes the entitlement.

SailPoint processes the revocation and the access is removed from the target application according to the configured workflow and provisioning process.

## 6. Common Issues

- Certification campaign not generated
- Reviewer not assigned correctly
- Certification items missing
- Access not visible to the reviewer
- Revocation not provisioned
- Certification remains pending
- Incorrect entitlement information

## 7. Troubleshooting

When a certification issue occurs:

1. Check the campaign configuration.
2. Verify the reviewer assignment.
3. Check the certification item.
4. Verify the user's entitlement information.
5. Check the provisioning result for revoked access.
6. Verify the target application.
7. Perform aggregation when required to reconcile the latest target-system state.

## Important Concept

Access Certification is primarily used to **review and validate existing access**.

If access is revoked during certification, the resulting revocation can be processed through SailPoint's provisioning mechanisms.

## Note

This is a hands-on learning/demo project created to demonstrate understanding of SailPoint IdentityIQ Access Certification. No confidential client or production data is used.
