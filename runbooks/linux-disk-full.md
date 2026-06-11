# Linux Disk Full Runbook

## Symptoms

- Root volume exceeds 90%
- Application failures
- Log generation stops

## Investigation

1. df -h
2. du -sh /*
3. Identify large logs
4. Identify heap dumps

## Resolution

- Archive old logs
- Remove unnecessary dumps
- Extend filesystem if required

## Prevention

- Scheduled cleanup jobs
- Disk monitoring alerts
- Log retention policies
