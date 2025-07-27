# Crontab Script
A crontab is a configuration file in Linux that allows scheduling the automated execution of tasks or commands at specific time intervals. The cron service manages these cron jobs. To edit the crontab, the command crontab -e is used, where tasks are written in a specific format that specifies when and what to execute. It is useful for automating repetitive tasks such as backups, updates, or system monitoring. <br>

1. Run a script every day at 6:30 AM
```
30 6 * * * /route/to/script.sh
```

2. Run a command every hour:
```
0 * * * * /route/to/script.sh
```

3. Run a script every 15 minutes:
```
*/15 * * * * /route/to/script.sh
```

4. Run a command every Monday at 8:00 AM:
```
0 8 * * 1 /route/to/script.sh
```

5. Run a script every first day of the month at 00:00:
```
0 0 1 * */route/to/script.sh
```
