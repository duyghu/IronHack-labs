Lab 7 – Shell Scripting
In this lab, I wrote shell scripts to manage files, monitor processes, create backups, parse logs, and schedule tasks. I used safety flags, logging, and parameterization in all scripts.
The scripts I created are:
common.sh – helper functions for logging and error handling
fm_tool.sh – find, archive, delete files with retention
proc_watch.sh – monitor processes, log CPU/memory, optional kill
backup.sh – create timestamped backups with verification and retention
log_parse.sh – parse logs (nginx/syslog) and summarize top information
I tested the scripts by creating demo files and directories. Archives, logs, backups, and summaries were successfully generated. Dry-run in fm_tool.sh helped check actions safely. Cron jobs were set up to automate backups and log parsing.
All outputs are in ~/lab7-outputs/, including archive files, log files, summary files, and the cron export.
