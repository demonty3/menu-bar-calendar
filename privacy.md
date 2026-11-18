# Privacy policy: Menu bar calendar

Last updated: 18 November 2026

Menu bar calendar is a personal tool that shows a Google Calendar in the macOS menu bar. It runs entirely on the Mac of the person who signs in. There is no server and no company behind it.

## What it reads

With your permission, the tool reads your Google Calendar through Google's read-only Calendar permission (`calendar.readonly`). That covers event times, titles, locations, notes and colours, and the list of your calendars with their colours.

It cannot create, change or delete events, and it does not read any other Google data such as email, contacts or files.

## What it does with that data

The data is used for one purpose: drawing your calendar in the menu bar of the same Mac.

## Where data is kept

- A copy of the next two weeks of events is kept in a cache file on the Mac, so the menu can be drawn without asking Google every minute. Each refresh replaces it.
- The Google sign-in is kept in the macOS Keychain on the Mac.

Nothing is stored anywhere else.

## Who it is shared with

Nobody. Calendar data is not sent to the developer or to any third party, and it is not used for advertising, analytics or training AI models. The only network requests the tool makes are to Google, to read the calendar.

If you click a location in the menu, that address opens in Apple Maps. If you click an event, it opens in Google Calendar in your browser.

## Removing access and data

- To remove the tool's access, go to your Google Account, open "Third-party apps and services" and remove Menu bar calendar.
- To remove the stored data, delete the `swiftbar-gcal` entries from the macOS Keychain and the `swiftbar-gcal` folder from `~/Library/Caches`.

## Google API Services User Data Policy

The tool's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Contact

Open an issue on [this page's repository](https://github.com/demonty3/menu-bar-calendar/issues).
