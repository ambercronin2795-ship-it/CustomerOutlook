# Owner Outlook CRM Web App

A single-user, browser-based CRM-style data-entry tool replicating the "Owner Outlook – Sheet1" form, built with React, Vite, and Tailwind CSS.

## Features

- Data entry for Tour Info, Owner Info, Maintenance, Contracts, and notes
- Auto-calculated fields (loan amortization, totals, etc.)
- Local data storage (IndexedDB)
- Backup/restore (JSON import/export)
- Clean printable PDF export (no gridlines/boxes)
- No authentication required

## Tech Stack

- React, Vite, Tailwind CSS
- idb-keyval, uuid, lucide-react, jspdf, html2canvas

## Run Locally

```bash
npm install
npm run dev
```

## Deploy (GitHub Pages)

1. Set `base` in `vite.config.ts` to your repo name.
2. Build: `npm run build`
3. Publish `dist/` via GitHub Pages.
