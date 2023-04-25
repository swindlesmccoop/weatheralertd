# Simple Inclimate Weather Alert Daemon

## Information
I use `curl` and `jq` to query and format data from the National Weather Service API, then send a notification for the most recent weather warning. It checks for a new warning every `$SLEEPTIME` seconds, which is set to 5 by default but should probably be set to 60 for practical uses.

Only works in the United States, sorry.
