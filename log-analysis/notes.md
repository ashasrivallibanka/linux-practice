# Log Analysis Lab

## Objective

Learn how to view, search, filter, and analyze log files in Linux.

## Commands Used

### View Log File

```bash
cat app.log
```

Purpose:
Display the entire log file.

### Search Errors

```bash
grep ERROR app.log
```

Purpose:
Display only error messages.

### Search Warnings

```bash
grep WARNING app.log
```

Purpose:
Display warning messages.

### Count Errors

```bash
grep ERROR app.log | wc -l
```

Purpose:
Count the number of error entries.

### View Logs Page by Page

```bash
less app.log
```

Purpose:
Navigate large log files efficiently.

### View Recent Logs

```bash
tail app.log
```

Purpose:
Display the latest log entries.

### Monitor Logs in Real Time

```bash
tail -f app.log
```

Purpose:
Watch log updates as they occur.

### Search Keywords

```bash
grep Database app.log
```

Purpose:
Find logs related to a specific service or component.

## Key Learnings

- Logs help identify application and system issues.
- grep is used to search specific log entries.
- tail displays recent log activity.
- tail -f monitors logs in real time.
- less helps navigate large log files.
- Log analysis is essential for troubleshooting.

## Real DevOps Usage

- Troubleshoot application failures
- Investigate server issues
- Monitor deployments
- Analyze system events
- Detect errors and warnings
- Debug production incidents
