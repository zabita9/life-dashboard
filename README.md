# Life, in progress

A personal dashboard for habits, goals, projects, books, trainings, and weekly reflection.

## Use the app

Open https://zabita9.github.io/life-dashboard/ in a modern browser. Create an account with your email and a password to sync your dashboard across browsers and devices. Supabase sends a confirmation email before first sign-in. Use the same account on each device.

Without signing in, entries stay in that browser on that device. With sign-in, the dashboard syncs through a private, row-secured Supabase table. The app stores no personal entries in the public GitHub repository.

## Reminders

Choose morning and evening times, then select **Enable notifications** and allow notifications in the browser. Reminders run while the app is open (including in a background tab). This version does not send reminders after the browser is fully closed.

The app is a static GitHub Pages site and uses Supabase Auth and the Supabase JavaScript client for sign-in and syncing.
