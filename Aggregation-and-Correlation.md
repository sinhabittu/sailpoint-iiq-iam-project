# Aggregation and Correlation – SailPoint IdentityIQ

## Objective

This document demonstrates the account aggregation and identity correlation process in SailPoint IdentityIQ.

## 1. Account Aggregation

Aggregation is the process of importing account and entitlement information from a target application into SailPoint IdentityIQ.

During aggregation, SailPoint can collect:

- Account information
- Account attributes
- Entitlements
- Account status

Example:

An Active Directory application contains an employee account:

Employee ID: EMP1001  
Username: avinash.k  
Department: IT

During aggregation, this account information is brought into SailPoint.

## 2. Identity Correlation

After account data is aggregated, SailPoint needs to determine which Identity owns the account.

Correlation rules or correlation configuration are used to match the target account with an existing Identity.

Example:

Target Account Employee ID = EMP1001

Identity Cube Employee ID = EMP1001

The account can therefore be correlated with the correct Identity.

## 3. Uncorrelated Account

If SailPoint cannot find a matching Identity for an account, the account may remain uncorrelated.

Common reasons include:

- Missing correlation attribute
- Incorrect attribute value
- Data mismatch
- Identity not yet created
- Incorrect correlation configuration

## 4. Troubleshooting

When an account is not correlated:

1. Check the aggregated account attributes.
2. Check the Identity attributes.
3. Verify the correlation configuration.
4. Verify the correlation rule, if used.
5. Check whether the expected Identity exists.
6. Re-run aggregation after correcting the source data or configuration.
7. Verify the account-to-Identity link.

## 5. Important Difference

### Aggregation

Brings data **from the target application into SailPoint**.

### Correlation

Determines **which SailPoint Identity belongs to the aggregated account**.

## Practical Flow

Target Application  
↓  
Account Aggregation  
↓  
Account Data Imported  
↓  
Correlation  
↓  
Identity Cube  
↓  
Account Linked to Identity

## Note

This is a hands-on learning/demo project created to demonstrate understanding of SailPoint IdentityIQ aggregation and correlation processes. No confidential client or production data is used.
