# Japan, together

A mobile-friendly travel companion for Hannah and Adam, 3–17 October 2026.

## Upload to GitHub
Extract this ZIP and upload all the extracted files to the root of your japan-trip repository. Upload the files, not the ZIP itself.

## Run
Serve this folder with any static web server, for example `python3 -m http.server 8000`, then visit http://localhost:8000.
No package installation or build step is required. Deploy the repository root with a static hosting provider.

## Features
- Day-by-day itineraries, maps, hotel details and bookings
- Food and sightseeing checklists
- Kyoto/Osaka weather from Open-Meteo
- JPY/GBP/HKD/USD/EUR conversion using Frankfurter reference rates, plus manual rates
- Editable flight details and links to airport boards / flight trackers
- Reminders and calendar exports
- Home-screen manifest and offline cache after a successful first visit

## Current limits
Automatic flight status/gate updates and background push notifications are not integrated. Browser reminders require the app to remain running. Import calendar files and confirm your calendar alert settings for closed-app reminders.
Personal edits and checklists are stored only on the current device; there is no shared sync.
Live weather and currency data require internet and provider availability.

The app contains personal trip and luggage details. Keep the repository private unless you choose to share those details.
