# Authorized Stress Testing Scope Template

Use this before running any load test, network stress test, or DDoS resilience validation.

## Authorization

Owner:

Approver:

Approval date:

Emergency contact:

## Target Scope

Approved targets:

- 
- 
- 

Approved ports:

- 
- 
- 

Out-of-scope systems:

- 
- 
- 

## Test Limits

Maximum duration:

Maximum packet rate:

Maximum bandwidth:

Maximum concurrency:

Approved test window:

## Allowed Methods

- Application load testing
- API load testing
- Layer 4 testing
- Layer 7 testing
- PCAP replay
- Packet chain replay

## Stop Conditions

Stop immediately if:

- Latency exceeds threshold
- Packet loss exceeds threshold
- Error rate exceeds threshold
- Legitimate users are affected
- Provider requests stop
- Emergency contact requests stop

## Monitoring

Track:

- Packet rate
- Bandwidth
- Latency
- Error rate
- Firewall drops
- WAF actions
- Provider mitigation events
- CPU and memory
- NIC drops
- Application queue depth

## Related Guide

https://retrostress.net/blog/legal-network-stress-testing-ddos-resilience
