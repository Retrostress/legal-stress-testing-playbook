# API Load Testing Checklist

Use this checklist for authorized API load testing and Layer 7 resilience validation.

## Before Testing

- Confirm API owner approval
- Define test accounts
- Define allowed endpoints
- Define excluded endpoints
- Set rate limits
- Set maximum concurrency
- Set test duration
- Confirm monitoring access
- Confirm stop conditions

## Test Real API Journeys

Include realistic flows:

- Authentication
- Read-heavy endpoints
- Write-heavy endpoints
- Search or filtering
- File upload or download
- Webhook handling
- Dashboard polling
- Health checks

## Metrics to Monitor

- Request latency
- p95 and p99 latency
- Error rate
- Status code mix
- Queue depth
- Database connections
- Slow queries
- Cache hit ratio
- WAF actions
- Rate-limit responses
- CPU and memory
- Autoscaling behavior

## During Testing

- Increase concurrency gradually
- Hold each step long enough to stabilize
- Watch user-facing outcomes
- Check WAF false positives
- Stop if error or latency thresholds are reached

## After Testing

- Identify the bottleneck
- Tune caching
- Tune rate limits
- Tune WAF rules
- Improve database paths
- Retest with the same profile

## Related Links

API load testing guide:

https://retrostress.net/blog/api-load-testing-ddos-resilience

API docs:

https://retrostress.net/docs/api-reference

RETRO//STRESS:

https://retrostress.net/
