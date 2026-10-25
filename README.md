# FORGE 4AM — personal PWA prototype

A private, offline-capable 12-week home workout tracker. Includes workouts, technique instructions, Ghanaian meal ideas, rest timer, local progress history, JSON backup, and calendar export.

## Run locally

From this directory: `python3 -m http.server 8000` then visit http://localhost:8000. For Android installation and offline use, deploy these static files to an HTTPS host (e.g. GitHub Pages or Netlify). Open the HTTPS URL in Android Chrome and choose Install app / Add to Home screen.

## Important limitations

- This is a **working first version**, not yet a hosted app. The app does **not** currently contain exercise photos or animations; written form cues are supplied instead.
- Web pages cannot reliably trigger wake-up alarms while closed. Set a recurring 3:45 AM alarm in Android Clock. Calendar export is a convenience and depends on calendar notification permissions.
- Progress records are stored in the current browser's localStorage and are not synced across devices. Export backups regularly.
- Nutrition is an initial estimate and not a verified individualized meal macro calculator.
- For a beginner at 116 kg, increase intensity gradually and seek medical advice before vigorous exercise if relevant health concerns exist.


## Exercise visual references v2
Seven AI-generated still images integrated: realistic-style Ghanaian trainer references for incline push-ups, squats, glute bridges, bird dogs, and 3D-style references for the first three. Tap VIEW in Workouts to switch modes. These are not verified movement videos; remaining exercises have written instructions only.
