# AIalarmclockcli
Build an alarm clock as a Python CLI application. CLI only no use any UI.

# Full command set:

set <time> [label] [--repeat] — add an alarm; --repeat fires it every 24 h
list — show all active alarms with IDs
cancel <id> — cancel by ID
snooze <id> [minutes] — default 5 min snooze
time — show current time
quit / exit — clean shutdown
