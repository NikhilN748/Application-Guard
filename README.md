# Application Guard

A single-file, offline job application tracker that helps you keep your applications organized and avoid conflicts — like applying to the same client twice or submitting too soon within a re-application window.

Everything lives in one `application-guard.html` file and runs entirely in your browser. No server, no build step, no accounts. Your data is saved locally via `localStorage`.

## Features

- **Check before applying** — flags conflicts and duplicate clients, and warns when you're inside a re-application window before you submit.
- **Multiple views** — switch between a **Board**, a **Ledger**, and a **Clients** list to track applications however you prefer.
- **Rich application records** — capture client, position title, position ID, role, job posting URL, resume link, locations (yours and the posting's), status, and free-form notes.
- **Status tracking** — mark applications as Applied and move them through your pipeline.
- **Risk indicators** — surfaces conflicts and re-application risk at a glance.
- **Search & sort** — filter by client, title, resume, or location, and sort each view independently.
- **Export** — download a CSV of your applications or a full JSON backup of your data.

## Usage

1. Download or clone this repository.
2. Open `application-guard.html` in any modern web browser.
3. Start adding applications — your data is saved automatically in the browser.

> **Tip:** Use **Export backup** regularly. Since data is stored in `localStorage`, clearing your browser data will remove it.

## Data & privacy

All data stays on your device in the browser's `localStorage`. Nothing is sent anywhere. To move your data between machines, use **Export backup** and import it on the other device.

## License

This project is provided as-is for personal use.
