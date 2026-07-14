Intro:
Created this with Claude as a way to view events in different time zones.
This is a learning project so may develop some bugs, will check in on the repo regularly. 
I hope to add a reminders feature built in to notify you of an event starting.

Reminder Limitations:
So a few honest limitations worth knowing
1. The tab needs to stay open (can be in the background/unfocused, just not closed) — there's no backend, so nothing can notify you if the page itself isn't loaded somewhere.
2. First click asks for browser notification permission — if someone denies it, a small note appears near the bell settings saying notifications are blocked, and reminders won't fire until they re-enable it in browser settings.
3. Reminders are stored in that browser's local storage, so they're personal to each visitor, same as the custom-events idea from before.
