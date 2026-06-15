# SNMP Monitoring Best Practices

## Overview

SNMP enables centralized monitoring of network devices, interfaces, CPU, memory, and environmental metrics.

## Key Metrics to Monitor

- Interface utilization
- Interface errors and discards
- CPU utilization
- Memory utilization
- Device availability
- Temperature and power status

## SNMP Versions

### SNMPv2c
- Community string based
- Simple deployment
- Less secure

### SNMPv3
- Authentication
- Encryption
- Recommended for production environments

## Monitoring Workflow

1. Configure SNMP on network devices
2. Add devices to monitoring platform
3. Validate polling
4. Configure alert thresholds
5. Review performance trends

## Common Alert Thresholds

- Interface utilization > 80%
- CPU utilization > 85%
- Memory utilization > 85%
- Device unreachable
- Excessive interface errors

## Best Practices

- Use SNMPv3 whenever possible
- Limit SNMP access with ACLs
- Monitor critical WAN links
- Review historical trends monthly
- Document monitored devices and alert policies
