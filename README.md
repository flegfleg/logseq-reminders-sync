# Logseq Reminders Sync

Two macOS shortcuts that enable sending and syncing reminders from Logseq to Reminders.app.

### Sync Logseq Todos to Reminders

Syncs Logseq todos with a deadline to the macOS Reminders app (see caveats). 
[Download shortcut](https://www.icloud.com/shortcuts/d69901f7a3a041c88ef668dff237536a).

### Send selected Logseq todo block to Reminders**: Sends the currently selected todo to reminders. 
[Download shortcut](https://www.icloud.com/shortcuts/57e9b847ef4d42b4aa3e208ebfe5cc21).

## Demo

https://github.com/flegfleg/logseq-reminders-sync/assets/4009931/a1c48236-8a9e-4895-b893-5359a92edb30


## Setup

1. Create a reminders list (e.g. „Logseq“)
2. Activate the Logseq API (https://docs.logseq.com/#/page/local%20http%20server) and set an API token.
3. Set your configuration in the „config“ dictionary at the top of the shortcut.

## Notes/Caveats

1. Adding/Editing todos in the Reminders.app will not be reflected in Logseq, only the todo status is synced (setting a todo as „Done“ in Reminders sets the todo as „Done“ in Logseq).
2. During the sync, a tag „processing-…“ will be created in Reminders. The tag may stay around for a few minutes until the Reminders.app interface updates.
3. Shortcut tested on macOS Ventura & Sonoma.


## Changelog

* 231225 : V1.2, Fix compatibility with macOS Sonoma
* 231122: V1.1, Fix reminders list name config was not applied
* 231121: V1.0, Initial Release
