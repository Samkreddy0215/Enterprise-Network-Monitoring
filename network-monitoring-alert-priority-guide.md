# Network Monitoring Alert Priority Guide

## Overview

A well-defined alert priority system helps network teams respond quickly to critical incidents while reducing alert fatigue.

## Priority Levels

### P1 – Critical

- Core router failure
- Data center outage
- WAN circuit down
- Firewall cluster failure
- Multiple site outage

**Action:** Immediate response (24x7)

---

### P2 – High

- BGP neighbor down
- OSPF adjacency failure
- High interface errors
- VPN tunnel down
- High CPU or memory utilization

**Action:** Investigate within 30 minutes

---

### P3 – Medium

- Interface utilization above 80%
- Device temperature warning
- Configuration backup failure
- Single access switch offline

**Action:** Resolve during business hours

---

### P4 – Low

- Informational Syslog messages
- Scheduled maintenance notifications
- Link utilization reports
- Inventory updates

**Action:** Review during routine maintenance

## Recommended Alert Sources

- SNMP
- Syslog
- NetFlow
- Prometheus
- Grafana
- SolarWinds
- Splunk

## Best Practices

- Eliminate duplicate alerts
- Define escalation procedures
- Review alert thresholds quarterly
- Document runbooks for common incidents
- Correlate alerts with monitoring dashboards
