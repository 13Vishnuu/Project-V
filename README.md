# Roche Site IT Support Hub 🖥️

An interactive, self-service troubleshooting dashboard designed to help Roche employees resolve common workstation hardware issues instantly, reducing the volume of unnecessary IT support tickets.

## 🚀 Key Features
* **Guided Troubleshooting**: Step-by-step instructions for Monitor, Charging, and Signal issues.
* **Centralized Analytics**: Integrated with **Google Apps Script** to log successful self-resolutions into a master Google Sheet.
* **Responsive Design**: Built with **Tailwind CSS** for a professional, widescreen dashboard experience.
* **WSD Integration**: Direct links to ServiceNow for raising IT or OFM (Facilities) tickets when hardware requires physical repair.

## 🛠️ Tech Stack
* **Frontend**: HTML5, JavaScript (ES6+), Tailwind CSS (via CDN).
* **Backend**: Google Apps Script (Web App).
* **Database**: Google Sheets.

## 📊 Impact Tracking
The hub includes a hidden analytics feature. Every time a user clicks a "Resolved" button, a ping is sent to a centralized Google Sheet. This allows the Site IT team to track:
1. Total tickets diverted.
2. Most common hardware issues.
3. Resolution success rates.

## 📂 Project Structure
```text
├── index.html          # Main dashboard logic and UI
├── dock.jpg            # Hardware visual aid
├── monitor1.jpg        # Hardware visual aid
├── monitor2.jpg        # Hardware visual aid
└── power.jpg           # Hardware visual aid
