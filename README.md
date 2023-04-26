# Simple Inclimate Weather Alert Daemon

## Dependencies
- `curl`
- `jq`
- `libnotify`

## Information
I use `curl` and `jq` to query and format data from the National Weather Service API, then send a notification for the most recent weather warning. It checks for a new warning in your state determined by your IP address every `$SLEEPTIME` seconds, which is set to 5 by default but should probably be set to 60 for practical uses.

An output of `null` means there are no reports for your area.

Only works in the United States, sorry.
