# Process Management Lab

## Objective

Learn how to monitor, identify, and manage Linux processes.

## Commands Used

### View Processes

```bash
ps
ps -ef

Purpose:
Display running processes.

Search Processes
ps -ef | grep bash

Purpose:
Find specific processes.

Real-Time Monitoring
top

Purpose:
Monitor CPU and memory usage.

Background Process
sleep 300 &
jobs

Purpose:
Run processes in the background.

Kill Process
kill PID

Purpose:
Stop a running process.

Key Learnings
Every running application is a process.
Each process has a unique PID.
top provides real-time monitoring.
jobs displays background jobs.
kill terminates running processes.
Real DevOps Usage
Monitor Jenkins processes
Check Docker services
Troubleshoot application issues
Analyze CPU and memory consumption
Stop unresponsive processes
