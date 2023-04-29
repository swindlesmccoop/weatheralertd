# Simple Inclimate Weather Alert Daemon

## Dependencies
- `curl`
- `libnotify`

## Information
I use `curl` to query data from the National Weather Service API, then send a notification for the most recent weather warning. It checks for a new warning in your state determined by your IP address every `$SLEEPTIME` seconds, which is set to 60 (one minute) by default.

Only works in the United States, sorry.
