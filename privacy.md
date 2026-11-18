## Privacy policy

Last updated: 18 November 2026

Menu bar calendar is a personal tool that shows a Google Calendar in the macOS menu bar. It is used by one person, its author, and runs entirely on that person's Mac. There is no server and no company behind it. This policy describes what the tool does with the calendar of whoever signs in to it.

## What it reads

With the signed-in person's permission, the tool reads their Google Calendar through Google's read-only Calendar permission (`calendar.readonly`). That covers event times, titles, locations, notes and colours, and the list of calendars with their colours.

It cannot create, change or delete events, and it does not read any other Google data such as email, contacts or files.

## What it does with that data

The data is used for one purpose: drawing the calendar in the menu bar of the same Mac.

## Where data is kept

- A copy of the events for the current week (from Monday, including days already past) and the following week is kept in a cache file on the Mac, so the menu can be drawn without asking Google every minute. A successful refresh overwrites it. If Google cannot be reached, the last good copy is kept and shown until the next successful refresh.
- The Google sign-in is kept in the macOS Keychain on the Mac.

Nothing is stored anywhere else.

## Who it is shared with

The tool does not send calendar data to its author or to anyone else on its own, and the data is not used for advertising, analytics or training AI models. The only network requests the tool itself makes are to Google, to sign in and to read the calendar.

There is one case where data leaves the Mac because of a click: choosing an event's location in the menu opens that address in Apple Maps, which sends the address text to Apple. Choosing "Open in Google Calendar" opens that day in Google Calendar in the browser.

## Removing access and data

- To remove the tool's access, go to the Google Account, open "Third-party apps and services" and remove Menu bar calendar.
- To remove the stored data, delete the `swiftbar-gcal` entries from the macOS Keychain and the `swiftbar-gcal` folder from `~/Library/Caches`.

## Google API Services User Data Policy

The tool's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Contact

Open an issue on [this page's repository](https://github.com/demonty3/menu-bar-calendar/issues).
