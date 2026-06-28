# Legal Stress Testing Scope Template

Use this template before running any network stress test, load test, or DDoS resilience validation.

## 1. Authorization

Test owner:

Approving person or organization:

Approval date:

Contact email:

Emergency contact:

## 2. Test Purpose

What are we trying to validate?

Examples:

- API performance under expected load
- DDoS mitigation behavior
- Game server stability
- Firewall or WAF rule effectiveness
- Provider scrubbing performance
- Incident response readiness

## 3. Targets In Scope

List only systems that are approved for testing.

| Target | Type | Ports | Notes |
|---|---|---|---|
| example.com | Web/API | 443 | Approved |
| 203.0.113.10 | Server | 80, 443 | Approved |

## 4. Out-of-Scope Systems

List systems that must not be tested.

| System | Reason |
|---|---|
| Third-party services | Not owned |
| Customer infrastructure | No written approval |
| Shared provider services | Not in scope |

## 5. Allowed Test Types

Allowed:

- Application load testing
- API performance testing
- Layer 4 resilience testing
- Layer 7 resilience testing
- PCAP replay testing
- Packet chain replay against approved targets

Not allowed:

- Testing third-party targets
- Traffic against home connections
- Unapproved IP ranges
- Attempts to bypass provider controls
- Any activity outside the written scope

## 6. Limits

Maximum duration:

Maximum packet rate:

Maximum bandwidth:

Maximum concurrent sessions:

Allowed test window:

Timezone:

## 7. Monitoring Plan

Monitor these during the test:

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

## 8. Stop Conditions

Stop the test immediately if:

- Latency exceeds agreed threshold
- Packet loss exceeds agreed threshold
- Error rate exceeds agreed threshold
- Legitimate users are affected
- Provider requests stop
- Emergency contact requests stop

## 9. Post-Test Report

After the test, record:

- Test timeline
- Traffic profile
- Expected behavior
- Actual behavior
- First bottleneck observed
- Mitigation behavior
- User impact
- Fixes required
- Retest date

## Related Guides

Legal network stress testing guide:

https://retrostress.net/blog/legal-network-stress-testing-ddos-resilience

What is an IP booter?

https://retrostress.net/blog/what-is-an-ip-booter

RETRO//STRESS getting started:

https://retrostress.net/docs/getting-started
