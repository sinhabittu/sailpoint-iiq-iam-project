# Provisioning and Deprovisioning – SailPoint IdentityIQ

## Objective

This document demonstrates the provisioning and deprovisioning process in SailPoint IdentityIQ.

## 1. Provisioning

Provisioning is the process of creating or modifying an account and granting the required access in a target application.

Example:

A new employee joins the IT department.

Required actions:

- Create an account in the target application.
- Assign the required role.
- Add required entitlements.

## 2. Provisioning Plan

SailPoint generates a provisioning plan that contains the requested account and entitlement changes.

A provisioning plan may contain:

- Account creation
- Account modification
- Account enable/disable
- Entitlement addition
- Entitlement removal
- Account deletion

## 3. Provisioning Flow

Identity/Lifecycle Event  
↓  
Access Evaluation  
↓  
Provisioning Plan Generated  
↓  
Approval, if required  
↓  
Provisioning Execution  
↓  
Target Application Updated

## 4. Deprovisioning

Deprovisioning is the process of removing or disabling access from a user.

Example:

When an employee leaves the organization:

- User access is revoked.
- Entitlements are removed.
- The target account may be disabled or deleted according to the organization's configuration.

## 5. Mover Scenario

When an employee changes department:

1. Old department access is identified.
2. Old access is revoked.
3. New department access is calculated.
4. A provisioning plan is generated.
5. New access is provisioned.

## 6. Verification

After provisioning or deprovisioning:

1. Verify the provisioning result.
2. Check the target application.
3. Confirm account status.
4. Verify entitlements.
5. Check for provisioning errors.
6. Perform aggregation when required to reconcile the target data with SailPoint.

## 7. Common Issues

- Provisioning plan not generated
- Approval pending
- Connector failure
- Invalid account attributes
- Entitlement not found
- Permission or authentication failure
- Target application unavailable
- Provisioning transaction failure

## Important Difference

### Provisioning

Giving or modifying access in the target application.

### Deprovisioning

Removing or disabling access from the target application.

## Note

This is a hands-on learning/demo project created to demonstrate understanding of SailPoint IdentityIQ provisioning and deprovisioning processes. No confidential client or production data is used.
