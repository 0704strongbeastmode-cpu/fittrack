# FitTrack MVP
Responsive German/English fitness web app with dark design.

## Run
Open `index.html` in a modern browser. To enable PWA install/offline caching, run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Included
- Training log (exercise, sets, reps, weight, notes)
- Food log (calories, protein, carbs, fat, meal type)
- Water intake tracking
- Body measurements (weight, body fat, waist, chest)
- Dashboard, German/English language toggle, mobile navigation
- Local browser persistence, delete entries, JSON export/import
- Basic PWA manifest and offline shell

## Not yet connected
This MVP stores data only in this browser on this device. Cloud accounts/sync and real Apple HealthKit / Android Health Connect or smartwatch integrations are not active; they require backend configuration, native platform code, permissions, and device testing. This is not yet published to app stores.
