---
bump: "patch"
type: "add"
---

Add "log_level" config option. This new option allows you to define the kind of messages
AppSignal's will log and up. The "debug" option will log all "debug", "info", "warning" and
"error" log messages. The default value is: "info"

The allowed values are:
- error
- warning
- info
- debug