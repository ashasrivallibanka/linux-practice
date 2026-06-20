# Cron Jobs Lab

## Objective

Learn how to automate Linux tasks using Cron Jobs.

## Commands Used

```bash
service cron status
crontab -e
crontab -l
chmod +x backup.sh
```

## Script Created

### backup.sh

```bash
#!/bin/bash

echo "Cron Job Executed at $(date)" >> cron.log
```

Purpose:
Write execution timestamps into a log file.

## Cron Schedule Used

```cron
*/2 * * * * /home/asha/devops-practice/linux-practice/cron-jobs/backup.sh
```

Meaning:
Run the script every 2 minutes.

## Cron Format

```text
* * * * *
| | | | |
| | | | Day of Week
| | | Month
| | Day of Month
| Hour
Minute
```

## Key Learnings

* Cron automates repetitive Linux tasks.
* Crontab stores scheduled jobs.
* Scripts should be tested before scheduling.
* Cron jobs can run backups, monitoring, and maintenance tasks.

## Real DevOps Usage

* Automated backups
* Log cleanup
* Health checks
* Monitoring scripts
* Scheduled deployments
* Database maintenance

