# Big E Workout Tracker

An installable, offline-first workout data app. It records weights, reps, completed sets, workout duration, and notes, with a four-day Planet Fitness routine preloaded as reusable templates.

Records stay on the phone in local storage. The Settings screen can export all records to a JSON backup and restore that backup on another device.

## Live app

https://ericdjenkins.github.io/Workout-Tracker/

## Android installation

Open the live app in Chrome on Android, tap the browser menu, then **Add to Home screen** or **Install app**.

## Local preview

Run a local web server in this folder, for example:

```bash
npx serve .
```

Then open the displayed address in a browser. Workout history is stored in the browser's local storage and can be exported from Settings.
