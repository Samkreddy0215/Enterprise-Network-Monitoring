# SNMP v2 vs SNMP v3

## Overview

Simple Network Management Protocol (SNMP) is widely used to monitor and manage enterprise network devices. SNMPv3 enhances security by adding authentication and encryption.

## SNMP v2 Features

- Community string authentication
- Read-only and read-write communities
- Simple deployment
- No encryption
- Suitable for trusted environments

## SNMP v3 Features

- User-based Security Model (USM)
- Authentication (MD5/SHA)
- Encryption (DES/AES)
- Message integrity
- Secure device management

## Comparison

| Feature | SNMPv2 | SNMPv3 |
|---------|---------|---------|
| Authentication | Community String | Username & Authentication |
| Encryption | No | Yes |
| Integrity Check | No | Yes |
| Security | Basic | High |

## Validation Checklist

- Verify SNMP service is enabled.
- Confirm monitoring server connectivity.
- Validate authentication credentials.
- Test polling using SNMP walk.
- Review monitoring dashboards.

## Best Practices

- Use SNMPv3 whenever possible.
- Disable default community strings.
- Use strong authentication credentials.
- Restrict SNMP access with ACLs.
- Monitor authentication failures.
