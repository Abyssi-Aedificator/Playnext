# PlayNext

A single-file gaming planner app with Gantt visualization, play order chains, changelog tracking, and Dropbox sync.

## Features

- **Game Management** — Add, edit, delete games with title, total hours, status tracking
- **Gantt Chart** — Visual timeline of your gaming schedule using dhtmlxGantt
- **Play Order Chains** — Link games into sequential play order (sequels, series)
- **Auto-computed Dates** — End dates calculated from your daily gaming hours
- **Changelog** — Automatic log of all changes made to your library
- **Dropbox Sync** — OAuth2 PKCE sync through your own Dropbox account
- **Customizable** — Dark/light theme, accent color picker, per-game Gantt bar colors
- **PWA** — Installable as a standalone app with offline caching

## Usage

1. Open `index.html` in any modern browser
2. All data is stored in your browser's localStorage
3. Configure your gaming hours in Settings to enable date estimates
4. Optional: Connect to Dropbox in Settings to sync across devices

## Setup

No build step or server required. Just open the file.

For Dropbox sync: Create a free Dropbox App at https://www.dropbox.com/developers/apps and enter the App Key in Settings.
