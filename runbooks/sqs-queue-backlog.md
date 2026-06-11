# SQS Queue Backlog Runbook

## Symptoms

- Queue depth increasing
- Delayed message processing
- CloudWatch alerts triggered

## Likely Causes

- Consumer application down
- Processing latency
- Downstream dependency failures

## Investigation Steps

1. Check CloudWatch queue metrics
2. Verify consumer application health
3. Review Kibana logs
4. Validate downstream services

## Resolution

- Restart consumer service
- Scale processing capacity
- Resolve downstream failures

## Prevention

- Tune alert thresholds
- Implement autoscaling
- Add backlog monitoring dashboards
