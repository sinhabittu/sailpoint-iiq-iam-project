# SailPoint IdentityIQ – Troubleshooting Scenarios

## 1. Aggregation Failed

### Symptoms
Account or entitlement data is not updated in SailPoint.

### Troubleshooting
1. Check application connection.
2. Verify credentials.
3. Check connector configuration.
4. Review aggregation logs.
5. Verify target-system availability.
6. Run aggregation again after fixing the issue.

---

## 2. Account Not Correlated

### Symptoms
The account appears as an uncorrelated account.

### Troubleshooting
1. Check the aggregated account attributes.
2. Verify the correlation attribute.
3. Compare the account attribute with the Identity attribute.
4. Check correlation configuration/rule.
5. Verify that the Identity exists.
6. Re-run aggregation after correcting the issue.

---

## 3. Provisioning Failed

### Symptoms
The provisioning request does not complete successfully.

### Troubleshooting
1. Check the provisioning request and provisioning plan.
2. Check approval status.
3. Review connector logs.
4. Verify target-system connectivity.
5. Check account attributes.
6. Verify entitlement values.
7. Check permissions and authentication.
8. Retry after fixing the root cause.

---

## 4. Entitlement Not Available

### Symptoms
Expected entitlement is not visible in SailPoint.

### Troubleshooting
1. Check entitlement aggregation.
2. Verify application schema.
3. Check entitlement mapping.
4. Verify the entitlement exists in the target system.
5. Re-run entitlement aggregation.

---

## 5. Provisioning Plan Not Generated

### Symptoms
Expected access changes are not included in the provisioning plan.

### Troubleshooting
1. Check the lifecycle event.
2. Verify role and entitlement configuration.
3. Check access policies.
4. Verify the requested access.
5. Check whether approval is required.
6. Review the workflow and provisioning configuration.

---

## 6. Certification Revocation Not Applied

### Symptoms
An entitlement is revoked during certification but remains in the target system.

### Troubleshooting
1. Check the certification decision.
2. Verify that the revocation was generated.
3. Check provisioning status.
4. Review connector logs.
5. Verify target-system connectivity.
6. Check the target account.
7. Run aggregation when required to reconcile the target state.

---

## 7. General Troubleshooting Approach

When troubleshooting a SailPoint issue:

**Identify → Reproduce → Check Logs → Validate Configuration → Find Root Cause → Fix → Retest → Verify**

## Note

These are hands-on learning/demo troubleshooting scenarios based on common SailPoint IdentityIQ IAM problems. No confidential client or production data is used.
