# PCAP Replay Workflow for Authorized Testing

PCAP replay can turn real traffic into repeatable resilience tests.

Only use packet captures you are authorized to collect and replay.

## Workflow

## 1. Capture Approved Traffic

Capture traffic only from systems you own or have permission to monitor.

Record:

- Capture source
- Capture time
- Approving person
- Target system
- Protocols involved
- Sensitive data handling

## 2. Sanitize the Capture

Before reuse:

- Remove sensitive payloads where possible
- Remove credentials
- Remove private customer data
- Store files with access control
- Document who can access the capture

## 3. Convert to a Repeatable Profile

Turn useful traffic into a replay profile or chain.

Record:

- Target
- Protocol
- Port
- Rate
- Duration
- Expected behavior
- Stop conditions

## 4. Replay Against Approved Targets

Replay only against systems in scope.

Monitor:

- Packet rate
- Latency
- Drops
- Errors
- CPU
- Firewall behavior
- Provider mitigation events

## 5. Compare Before and After

Use the same profile after remediation.

Compare:

- Error rate
- Packet drops
- Latency
- Clean traffic delivery
- Server stability
- Recovery time

## Related Links

RETRO//CAPTURE:

https://retrostress.net/capture

Capture guide:

https://retrostress.net/docs/capture

Chain builder guide:

https://retrostress.net/docs/chain-builder

PCAP replay blog:

https://retrostress.net/blog/pcap-replay-load-testing
