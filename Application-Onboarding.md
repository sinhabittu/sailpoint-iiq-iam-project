# SailPoint IdentityIQ – Application Onboarding

## Objective

The objective is to onboard a target application into SailPoint IdentityIQ so that accounts and entitlements can be managed through IAM processes.

## 1. Gather Application Details

Before onboarding, collect:

- Application name
- Application owner
- Application type
- Connection details
- Authentication method
- Account attributes
- Entitlement attributes
- Provisioning requirements

## 2. Select Connector

Select the appropriate connector based on the target system.

Examples:

- Active Directory
- LDAP
- JDBC
- REST / Web Services

## 3. Configure Connection

Configure the connection properties required to communicate with the target system.

## 4. Configure Schema

Define the account and entitlement attributes that SailPoint needs to manage.

Example account attributes:

- Account ID
- Employee ID
- Username
- Email
- Department
- Status

## 5. Configure Correlation

Configure correlation so SailPoint can match accounts from the target system with existing identities.

Example:

Target account Employee ID → SailPoint Identity Employee ID

## 6. Configure Aggregation

Configure and run aggregation to bring account and entitlement data from the target application into SailPoint.

Verify:

- Accounts
- Account attributes
- Entitlements
- Account status

## 7. Configure Provisioning

Configure provisioning so SailPoint can perform actions such as:

- Create account
- Modify account
- Disable account
- Delete account
- Add entitlement
- Remove entitlement

## 8. Testing

Perform the following tests:

1. Run account aggregation.
2. Verify account data.
3. Verify correlation.
4. Verify entitlements.
5. Test account provisioning.
6. Test entitlement provisioning.
7. Test deprovisioning.
8. Verify changes in the target system.

## 9. Troubleshooting

Common onboarding issues:

- Connection failure
- Authentication failure
- Incorrect schema mapping
- Correlation failure
- Aggregation failure
- Provisioning failure
- Incorrect entitlement mapping

## Conclusion

Application onboarding connects a target application with SailPoint IdentityIQ and enables centralized identity, account and entitlement management.

> This is a hands-on learning/demo project and does not contain any confidential client or production data.
