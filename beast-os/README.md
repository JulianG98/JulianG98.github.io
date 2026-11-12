# Beast OS

Mobile-first PWA prototype for Julian's tactical fitness cockpit.

## Local preview

```bash
python3 -m http.server 4173 --directory /data/fitness-app
```

Open http://127.0.0.1:4173

## Current prototype

- Command Center dashboard
- Today's mission and exercise targets
- Garmin sleep/recovery card
- Progression and nutrition cards
- Responsive mobile layout
- Installable PWA shell

The displayed values are a verified UI prototype snapshot. The next build step is to replace the snapshot adapter with the existing Garmin/FDDB/OneNote sync outputs and add real set logging.
