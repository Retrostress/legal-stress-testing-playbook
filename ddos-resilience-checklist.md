# DDoS Resilience Testing Checklist

Use this checklist for authorized DDoS resilience testing.

## Before Testing

- Confirm written authorization
- Define targets in scope
- Define systems out of scope
- Notify hosting provider or mitigation vendor if needed
- Set test window
- Set maximum intensity
- Set stop conditions
- Confirm emergency contacts
- Baseline normal traffic

## Metrics to Capture

- Packet rate
- Bandwidth
- Latency
- Error rate
- Firewall drops
- WAF actions
- Provider mitigation events
- CPU and memory
- NIC drops
- Connection counts
- Application queue depth
- Database or cache pressure

## During Testing

- Start with low intensity
- Increase gradually
- Watch infrastructure and user-facing metrics
- Record timestamps for alerts and mitigation events
- Stop if thresholds are reached
- Do not change multiple defenses at once

## After Testing

- Identify the first bottleneck
- Document what held and what failed
- Assign remediation owners
- Save the traffic profile
- Retest after fixes

## Helpful Resources

RETRO//STRESS legal stress testing guide:

https://retrostress.net/blog/legal-network-stress-testing-ddos-resilience

Methods catalog:

https://retrostress.net/methods

Getting started:

https://retrostress.net/docs/getting-started
