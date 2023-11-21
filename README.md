# Logseq Reminders Sync


Two shortcuts that enable sending and syncing reminders from Reminders to Logseq.

**Sync Logseq Todos to Reminders**: Syncs Logseq todos with a deadline to the macOS Reminders app (see caveats).

**Send selected Logseq Todo to Reminders**: Sends the currently selected todo to reminders. 

## Demo




## Setup

1. Create a reminders list (e.g. „Logseq“)
2. Activate the Logseq API (https://docs.logseq.com/#/page/local%20http%20server) and set an API token.
3. Set your configuration in the config dictionary in the shortcut.

## Notes/Caveats

1. Adding/Editing todos in the Reminders.app will not be reflected in Logseq, only the todo status is synced (setting a todo as „Done“ in Reminders sets the todo as „Done“ in Logseq).
2. During the sync, a tag „processing-…“ will be created in Reminders. The tag may stay around for a few minutes until the Reminders.app interface updates.


## Changelog

* 231121: V1.0, Initial Release