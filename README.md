# Logseq Reminders Sync

Two macOS shortcuts for sending and syncing reminders from Logseq to Reminders.app. Logseq’s task management features are fine, but i really like the system integration of Apple Reminders. 

## Sync Logseq Todos to Reminders — V 1.3

Sync Logseq todos marked as NOW and those with a deadline to the macOS Reminders app (see caveats). 
[Download shortcut](https://www.icloud.com/shortcuts/71bfe5ac71e94de2bd84fa55d2f281df).

### Bonus shortcut: Send selected Logseq todo block to Reminders: Sends the currently selected todo to reminders

[Download shortcut](https://www.icloud.com/shortcuts/57e9b847ef4d42b4aa3e208ebfe5cc21).

## Demo

https://github.com/flegfleg/logseq-reminders-sync/assets/4009931/a1c48236-8a9e-4895-b893-5359a92edb30


## Setup

1. Create a reminders list (e.g. „Logseq“)
2. Activate the Logseq API (https://docs.logseq.com/#/page/local%20http%20server) and set an API token.
3. Set your configuration in the „config“ dictionary at the top of the shortcut.

## Notes/Caveats

1. This is a pretty complex shortcut, and Logseq block identifiers (uids) can change (e.g. if you do a Re-Index). Use at your own risk. 
2. Adding/Editing todos in the Reminders.app will not be reflected in Logseq, only the todo status is synced (setting a todo as „Done“ in Reminders sets the todo as „Done“ in Logseq).
3. During the sync, a tag „processing-…“ will be created in Reminders. The tag may stay around for a few seconds until the Reminders.app interface updates.
4. Shortcut tested on macOS Ventura & Sonoma.


## Changelog

* 231225 V.1.3, Include NOW tasks (with and without deadlines)
* 231225 : V1.2, Fix compatibility with macOS Sonoma
* 231122: V1.1, Fix reminders list name config was not applied
* 231121: V1.0, Initial Release
