# Daraio Lab Research Portal

A single-file web portal for managing lab resources at the Daraio Research Group, Caltech.

## Features
- 📦 Equipment Inventory
- 🧪 Chemical Inventory
- 📁 Projects Tracker
- 🔬 Instruments & Booking Calendar
- 💎 High-Value Items Registry
- 🔐 Admin Panel (change history, QR codes, settings, backup/restore)
- 🌙 Dark mode
- 🔍 Global search
- 🖨 Print & export

## How to use
All data is stored locally in your browser's `localStorage`. No server or login backend required.

- **General access code:** `1234` (change in Admin → Settings)
- **Admin access code:** `0000` (change in Admin → Settings)

## Deployment
This is a single `daraio-lab.html` file. To update the live site, simply replace this file with the new version.

## Notes
- Data is stored per-browser. Use **Admin → Settings → Download Full Backup** to export and share data between machines.
- QR codes for instruments can be configured in **Admin → QR Codes** once the live URL is known.
