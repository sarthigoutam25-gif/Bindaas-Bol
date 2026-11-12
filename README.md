# Bindaas Bol

Let's Play With English. A mobile-first web app (installable PWA) for learning spoken English.

## What is in the app
- Mobile OTP login (demo mode) and student profile
- Level test: Listening, Reading, Speaking, Writing, Vocabulary, Grammar. 5 questions each, randomised every time
- Lessons: video, test (70% to pass), 1 to 5 min speaking video, then recorded video conversation
- Free audio conversations (max 7 min, 7 free sessions), then 2 sessions for Rs 9 or unlimited with any paid course
- Courses, booking, dashboard, notifications

## Demo limits
OTP, payments, microphone, camera and video calls are simulated. Progress is stored in the browser only.
A real release needs a backend (for example Firebase for OTP, data and recordings, and a WebRTC service for calls).

## Publish with GitHub Pages
1. Create a new repository on GitHub and upload these files (or push with git).
2. Open Settings > Pages and set Source to GitHub Actions.
3. Push to `main`. The workflow in `.github/workflows/pages.yml` publishes the site at `https://<your-username>.github.io/<repo>/`.

## Install on Android
Open the site in Chrome, then tap the menu and choose Install app.

## Make an APK
Paste the published address into https://www.pwabuilder.com and download the Android package.
