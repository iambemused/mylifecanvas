# MyLifeCanvas

Personal task and life management, by MoMo Creative.
Perth, Western Australia.

A self-contained suite of three single-file web apps for organising your tasks,
priorities, and personal data — entirely in your browser, with no accounts and
no server-side data.

## The suite

| App | Path | What it does |
|---|---|---|
| **MyLifeCanvas** | `/` | The main task and life management workspace |
| **Quick Capture** | `/quickcapture` | A mobile-friendly companion for fast on-the-go task entry |
| **Data Export Helper** | `/export-helper` | A utility for backing up and restoring your data |

## Privacy

All three apps run entirely in your browser. Your data lives in your browser's
local storage and never leaves your device. No accounts, no cloud sync, no
tracking.

To move data between devices, use the Quick Capture export → main app import
flow, or the Data Export Helper for full backups.

## Architecture

Each app is a single HTML file with React/Babel rendered in-browser. No build
step. To update, edit the HTML file directly and push.

## Deployment

This repo deploys automatically to Netlify (`my-lifecanvas.netlify.app`) on push
to `main`.

## Licensing

Personal use: free. Commercial use: requires written permission from MoMo
Creative. Get in touch via [the-clan.wixsite.com/momocreative](https://the-clan.wixsite.com/momocreative).

---

© MoMo Creative · ko-fi.com/momocreative
