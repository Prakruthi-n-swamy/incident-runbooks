# Example Postmortem

## Incident

SQS consumer outage causing message backlog.

## Impact

Delayed order processing for 30 minutes.

## Root Cause

Consumer service failed due to dependency timeout.

## Resolution

Service restarted and dependency issue corrected.

## Preventive Action

Added dependency health checks and alerting.
